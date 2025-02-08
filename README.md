##  Terraform to spin up a Docker container for an nginx server

### Install Terraform

[Hahicorp Instructions](https://developer.hashicorp.com/terraform/install)

#### Mac example

`brew tap hashicorp/tap`

`brew install hashicorp/tap/terraform`


### Intialize

`terraform init`

### Provision the server

`terraform apply`

### Check for the Docker container

`docker ps`

### Test locally

Visit [localhost:8000](localhost:8000)

### Take it down

`terraform destroy`

