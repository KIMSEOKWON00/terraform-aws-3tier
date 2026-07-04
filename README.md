# terraform-aws-3tier

AWS 3-tier 인프라(VPC, ALB/ASG/EC2, CodeDeploy, ECR, CloudFront/S3)를 Terraform으로 구성해본 개인 학습 프로젝트입니다.

## 실행 방법

```bash
cd Terraform_Project/environments/dev
terraform init
terraform plan
terraform apply
