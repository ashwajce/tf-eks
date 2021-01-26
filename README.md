# Setting up 1 node EKS cluster using terraform

This repo consists of terraform modules which can be used to a spin up small 1 EC2 node EKS cluster along with Nginx ingress controller.

# Prerequisites 
You need to install below applications/configuration before spinning up EKS cluster
- Terraform application version \>= 0.12
- Valid AWS account to create AWS resources

# How to Install
Please follow below steps to install EKS and NGINX ingress controller

Step 1:
Insall plugins in local

```sh
$ terraform init
```

Step 2:
Generates a speculative execution plan, showing what actions of Terraform.
```sh
$ terraform plan
```
Step 3: Apply terraform configuration 
```sh
$ terraform apply
```

After applying the configuration terraform will take 15-20 minutes to spinup EKS cluster and all other resources.

