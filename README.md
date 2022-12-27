# terraform-github-Actions
This Action defines a job called build that runs on an Ubuntu runner. It installs Terraform, sets up the AWS credentials using the aws-actions/configure-aws-credentials action, and runs the terraform init , terraform plan and terraform apply commands.

You will need to replace us-east-1 with your desired AWS region, and set the AWS_ACCESS_KEY_ID and AWS_SECRET_ACCESS_KEY secrets in your repository settings with your own AWS credentials.