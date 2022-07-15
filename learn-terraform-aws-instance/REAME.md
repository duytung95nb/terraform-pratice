# Purpose
This workspace is for praticing terraform with Aws
# Prerequisites
- Install aws cli: https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
    For linux, run:
        curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
        unzip awscliv2.zip
        sudo ./aws/install
- Authenticate aws:
    Run: export AWS_ACCESS_KEY_ID=<your-aws-access-key-id>
    Run: export AWS_SECRET_ACCESS_KEY=<your-aws-secret-access-key>
# Run
- Move to current folder, run: terraform init
- Check terraform plan (targeted result after applying code to infra): terraform plan
- Provision infra: terraform apply
- Destroy infra: terraform destroy