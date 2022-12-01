# Variables
[Variables](https://terraform.io/language/values/variables) allow
values to be reused throughout your configuration without duplication. Add a 
new variable called `foo` to `~/main.tf`:

```editor:append-lines-to-file
file: ~/sample/main.tf
text: |
    variable "foo" {
      description = "a variable for our template"
      default = "rose"
    }
```

Now lets change the variable passed to the `example` template from:

```editor:select-matching-text
file: ~/sample/main.tf
text: 'foo = "rose"'
```

to:

```editor:replace-text-selection
file: ~/sample/main.tf
text: "foo = var.foo"
```


Now run a `plan`:

```execute-1
terraform plan
```

You should see output including is line:

```
No changes. Infrastructure is up-to-date.
```

Now change the `foo` variable from

```editor:select-matching-text
file: ~/sample/main.tf
text: "rose"
```

to

```editor:replace-text-selection
file: ~/sample/main.tf
text: "daisy"
```

Now run a `plan` again:

```execute-1
terraform plan
```

This time you should see some changes:

```
  - A rose by any other name would smell as sweet.
  + A daisy by any other name would smell as sweet.
```

Apply the changes:

```execute-1
terraform apply
```

Again, type `yes` when prompted.

```execute-1
yes
```

View the contents of the file with the `cat` command:

```execute-1
cat example.txt
```
