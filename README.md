This is full source code to the article Terraform recipe - How to create AWS ElasticSearch cluster

Launch instructions
Modify defaults.tfvar according to your needs.

Execute the following commands:

terraform init
terraform plan -var-file=defaults.tfvar
terraform apply -var-file=defaults.tfvar
