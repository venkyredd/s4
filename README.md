# S3 + CloudFront Deployment with Terraform & GitHub Actions

## Steps to Deploy:
1. Run `terraform init && terraform apply -auto-approve` to create the infrastructure.
2. Push your changes to GitHub, and GitHub Actions will deploy automatically.
3. Access your site using the CloudFront URL from Terraform output.
