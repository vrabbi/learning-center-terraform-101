# Providers
A [provider](https://terraform.io/language/providers) is an abstract
way of handling the underlying infrastructure and responsible for managing the
lifecycle of a resource. Providers are responsible for understanding API
interactions and exposing resources.

Providers are plugins released on a separate rhythm from Terraform itself, and
so they have their own version numbers. For production use, you should
constrain the acceptable provider versions via configuration, to ensure that
new versions with breaking changes will not be automatically installed by
Terraform in the future.

Terraform works based on configuration files, in this case `~/main.tf`. The
The integrated vscode editor lets you edit the `~/main.tf` file.

To constrain the provider version as suggested, add a `required_providers`{{}}
block inside a `terraform` block. Let's do this for the
[template](https://registry.terraform.io/providers/hashicorp/template/latest/docs)
provider.  


First lets create a directoryh and create a base file:  
```execute-1
mkdir sample
touch sample/main.tf
cd sample
```  

Now lets copy the code below to `main.tf` using the editor tab

```editor:append-lines-to-file
file: ~/sample/main.tf
text: |
    terraform {
      required_providers {
        template = {
          version = "~> 2.0"
        }
      }
    }
```

Now run [init](https://terraform.io/cli/commands/init)  and observe
the output:

```execute-1
terraform init
```

You should see output including these lines:

```
- Downloading plugin for provider "template" (hashicorp/template) 2.2.0...

Terraform has been successfully initialized!
```
