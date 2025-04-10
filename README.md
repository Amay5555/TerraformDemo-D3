# Create main.tf file
In the main.tf file enter the docker image you want to pull from dockerhub (ngninx in this case). Expose ports to make the site accessible.
# Setting up Terraform
## terraform init       : download required pulgins (Docker provider). 
## terraform plan       : displays the execution plan of terraform.
## terraform apply      : provisions a docker container and run nginx on the it.
## terraform state list : lists all the resources currently being tracked in the state file (terraform.tfstate).
## terraform state show : displays the details about a specific resource.
<img width="746" alt="terraform state" src="https://github.com/user-attachments/assets/ba8230f8-254c-413d-bdb8-e33d2cc190d3" />

## terraform destory    : destroys the resources created by the terraform configuration.

