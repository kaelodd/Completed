**Azure DevOps**

This is the beginning of a multi-part series looking into deploying Terraform using Azure DevOps. There are several goals I want to accomplish in this project.

1. From Your local repos, push the files to your Azure Repos
1. The file webapp.tf is our terraform file to create our resources, app service plan, web app and storage.
1. Create a pipeline in Azure DevOps using .Net core
1. Validate the Terraform code as part of the pipeline (validate and format)
1. Run a CI on the project where you Restore, Build, Test, Publish, Copy Terraform file to artifact and Publish Artifact.
1. Proceed to Continuous Deployment.
1. Deploy Azure Resources, run script to get storage key.
1. Replace token in terraform file
1. Install Terraform, Terraform Init, plan, apply and approve.
1. Finally deploy into Azure web app service 
1. Resource group will be generated with storage account used to store terraform.tfstate.
1. Another resource group will be created which houses the web app and service plan.


