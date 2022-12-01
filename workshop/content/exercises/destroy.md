# Destroying Resources
Terraform not only creates and updates resources, it also makes it easy to 
[destroy](https://terraform.io/cli/commands/destroy) resources 
managed by the configuration.

Let's delete our `example.txt` file:

```execute-1
terraform destroy
```

You should see output including this line:

```
Plan: 0 to add, 0 to change, 1 to destroy.
```

Type `yes` and hit enter.

You should then see:

```
Destroy complete! Resources: 1 destroyed.
```

Verify that `example.txt` has been deleted:

```execute-1
cat example.txt
```{{exec}}

Which should say `No such file or directory`
