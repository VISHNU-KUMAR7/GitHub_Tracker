Common cmd are below

terraform plan

terraform init

terraform fmt

terraform apply

terraform apply --auto-approve

terraform taint <remote_resource_name>.<local_resource_name>

terraform output

terraform console.

terraform validate


WE save credentials globally. 
export TF_VARS_<key>=<value>


For Every resource try to make a separate file. 


keep all variables in a file. Name as "terraform.tfvars"

Each varible need to initilied before  
variable "block"{
type
}
