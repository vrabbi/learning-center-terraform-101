# Installing Terraform
For this workshop we will need to download and install the Terraform binary which can be done by running the following commands:

```execute-1
curl -o terraform.zip -fsSL https://releases.hashicorp.com/terraform/1.1.9/terraform_1.1.9_linux_amd64.zip
unzip terraform.zip
install -t /opt/eduk8s/bin terraform
```  

To Validate the installation run:
```execute-1
terraform version
```

This should output text similar to:

```
Terraform v1.2.5
on linux_amd64
```

Now we are ready to start learning terraform
