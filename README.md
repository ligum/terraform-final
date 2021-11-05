   ![image](https://bootcamp.rhinops.io/images/terraform-logo.png)

# Project Overview


In this week’s project we are going to recreate the infrastructure of the WeightTracker application but this time instead of doing it manually we are going to use Terraform to automate this process. The infrastructure that you have to deploy is the same as last week’s project with the first bonus (High Availability).


   ![image](https://bootcamp.rhinops.io/images/week-4-project-env.png)



## Goals (Project-3-Bonus)
Use Terraform to define all the infrastructure

Use Terraform variables to configure at least 5 parameters for your template

Configure a Terraform output to retrieve the VM password (Linux servers must be configured with password authentication instead of SSH keys)

Create a terraform module to reuse the code that creates the virtual machines

Install the WeightTracker application and the Database into the VMs created by terraform (the installation can be done manually)

Ensure the application is up and running (and work automatically after reboot)

## Considerations
Remember to run terraform destroy during the development to avoid spending too much from your student credits (provision it prior your delivery)

Manage the entire project on Git

Remember to keep your code clean and documented

Ensure your Network Security Group (NSG) allows you to access the servers and allows communication between the web server and the database

Make sure the database cannot be accessed from the internet (it’s not publicly exposed)

Take into account that you have a limited budget so keep servers down when not needed and use the smallest instances possible to keep costs low

## Expected Result
A Terraform template that deploys the required infrastructure

The WeightTracker application up and running

Database server is not accessible from the internet

Ensure that your application and databases start automatically when an instance is rebooted

## Bonus
Use a Terraform backend to store the Terraform state in Azure Blob Storage

Use the Azure PostgreSQL managed service instead of a VM (Bonus “B” from previous week)

Implement the bonus “C” (Elasticity) from the previous project using Terraform
