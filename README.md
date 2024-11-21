GitOps Infrastructure Pipeline:

This project implements a GitOps-driven Infrastructure as Code (IaC) pipeline to automate and manage the provisioning of cloud resources and application infrastructure. The pipeline uses version-controlled configuration and leverages Git as the single source of truth for infrastructure state.

# Terraform code 

## Maintain vpc & eks with terraform for vprofile project

## Tools required
Terraform version 1.6.3 - 2.0.0

### Steps
* terraform init
* terraform fmt -check
* terraform validate
* terraform plan -out planfile
* terraform apply -auto-approve -input=false -parallelism=1 planfile
####
#####
