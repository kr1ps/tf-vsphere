# Terraform vSphere

This repo deploy a new vm on vsphere from an existing vm-template  using Hashicorp's terraform automatically.

## How to use this repo

### Pre-requesites

Make sure you have [Terraform](https://learn.hashicorp.com/tutorials/terraform/install-cli) Version v1.1.3 or later installed.

### Step 1: Adjust variables

Rename the file [example-terraform.tfvars](example-terraform.tfvars) to `terraform.tfvars` and adjust the variables for your VMware vSphere environment. Some documentation on each variable is inside the sample file.
```bash
mv example-terraform.tfvars terraform.tfvars
vim terraform.tfvars
```

### Step 2: Init Terraform

Init Terraform by using the following command.
```bash
terraform init
```

### Step 3: Terraform plan

Terraform Plan by using the following command.
```bash
terraform plan
```

### Step 4: Terraform apply

Terraform apply by using the following command.
```bash
terraform apply
```