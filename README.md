# terraform-aws-production-infra
I designed and deployed a production-ready, multi-AZ AWS infrastructure using Terraform with reusable modules, remote state, and environment separation

terraform-aws-production-infra/
├── modules/
│   ├── vpc/
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── outputs.tf
│   ├── security/
│   ├── alb/
│   └── ec2/
│
├── environments/
│   ├── dev/
│   │   ├── backend.tf
│   │   ├── main.tf
│   │   ├── variables.tf
│   │   └── terraform.tfvars
│   └── prod/
│
├── providers.tf
├── versions.tf
└── README.md
