How to Deploy This VM (Step-by-Step)
# 1. Login to Azure
az login

# 2. Initialize Terraform
terraform init

# 3. Validate (recommended)
terraform validate

# 4. Deploy Infrastructure
terraform apply -auto-approve
