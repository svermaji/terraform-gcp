# Terraform

> Will create multiple set of scripts for clarity.
> Version details:
>    - OS: Win10 Home
>    - Terraform: vterraform_1.4.6_windows_386

## 1-beginner 
For details check my blog: http://sv-technical.blogspot.com/2019/12/terraform.html<br>
This folder contains terraform sample scripts that
  - creates roles, users (not using for security reasons)
  - creates instance using ssh
  - creates groups
  - ami
  - ec2 etc

Commands:
 - `terraform plan -no-color -refresh=true -out=infra.tfplan`
 - `terraform apply -refresh=true -auto-approve "infra.tfplan"`
 - `terraform destroy -auto-approve`
 
