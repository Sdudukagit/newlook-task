# NewLook Task

This repository contains the Terraform code for provisioning and managing infrastructure for Azure Kubernetes Service. The infrastructure is defined as code, allowing for version control, collaboration, and reproducibility. Also this repository contains CRUD API created in Nodejs. Also created CI/CD Pipeline with Github Actions which will continously looks after the code i.e. API, as soon as there is change in code it will trigger pipeline create docker image & push into AKS 
cluster automatically.

## Prerequisites

Before using this Terraform code, make sure you have the following prerequisites installed:

- [Terraform](https://www.terraform.io/downloads.html): Ensure that you have the latest version of Terraform installed on your system.
- [Azure-CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli): Ensure that you have the latest version of Azure-CLI installed on your system.
- [Kubectl](https://kubernetes.io/docs/tasks/tools/)


## Getting Started

To provision the infrastructure using Terraform, follow the steps below:

1. **Clone this repository** to your local machine:
   ```bash
   git clone <repository-url>
   cd terraform-infra
   terraform init
   terraform plan
   terraform apply --auto-approve
   '''
   
