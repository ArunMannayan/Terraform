# Terraform code for VPC creation

##### Terraform code for VPC creation in an AWS region with multiple subnets (Both private and public) in different availability zones.

###### Code included,

- Variable declaration
- VPC Creation
- Elastic IP registeration
- Private and Public subnets creation
- Internet Gatewat and NAT Gateway creation
- Route Table creation and association.

###### For Terraform installation,


>https://learn.hashicorp.com/tutorials/terraform/install-cli?in=terraform/aws-get-started

###### How to configure?


>_Replace the contents with in "" with your valid data in the file metioned below_
```sh
# vi terraform.tfvars
region = "Specify_your_region"
access_key = "IAM Your access key"
secret_key = "IAM Your Secret key "
project = "Project name"
vpc_cidr = "Specify the cidr block (eg: 172.16.0.0/16)"
```
###### How to use?


```sh
$ git clone https://github.com/ArunMannayan/Terraform.git
$ cd terraform 
$ terraform init
$ terraform plan
$ terraform apply -auto-approve
```


