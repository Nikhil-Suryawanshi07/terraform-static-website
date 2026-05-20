# Terraform Static Gaming Website Hosting on AWS S3

This project uses Terraform to host a static gaming website on AWS S3.

Terraform automatically:
- Creates an S3 bucket
- Enables static website hosting
- Uploads HTML website files
- Configures public access
- Generates the website URL

---

# Project Structure

terraform-project/

├── provider.tf
├── variables.tf
├── terraform.tfvars
├── main.tf
├── index.html
└── README.md

---

# Technologies Used

- Terraform
- AWS S3
- HTML
- CSS

---

# Step 1 - Configure AWS Provider

File: provider.tf

provider "aws" {
  region = "ap-south-1"
}
