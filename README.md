# terraform-s3-backend-lab

See lab instructions on D2L.

1. When is the state file created?
- when you run `terraform apply` the first time, the terraform state file will be created
2. When is the lock file present?
- The first time you run `terraform init`, terraform will generate the lock file ".terraform.lock.hcl"
3. Is the lock file always in the bucket after it is created?
- No,the lock file is temporary and it will disappear once the Terraform operation finishes.

("Screenshot 2025-11-25 143406.png")
