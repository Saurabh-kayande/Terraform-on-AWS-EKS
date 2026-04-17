# Terraform-on-AWS-EKS
# TERRAFORM + AWS + EKS 
```
𝘈𝘶𝘵𝘰𝘮𝘢𝘵𝘦 𝘗𝘳𝘰𝘷𝘪𝘴𝘪𝘰𝘯𝘪𝘯𝘨 𝘰𝘧 𝘒𝘶𝘣𝘦𝘳𝘯𝘦𝘵𝘦𝘴 𝘊𝘭𝘶𝘴𝘵𝘦𝘳𝘴 𝘰𝘯 𝘈𝘞𝘚 𝘸𝘪𝘵𝘩 𝘛𝘦𝘳𝘳𝘢𝘧𝘰𝘳𝘮
```

## 🛡️ 2026 DevSecOps Enhancements (What You Will Learn)
This repository contains raw Terraform code for EKS provisioning. In a 2026 DevSecOps context, raw IaC execution is prohibited without the following guardrails:
1. **IaC Static Analysis:** Before `terraform apply` is ever run, the code must be scanned by tools like **tfsec**, **kics**, or **checkov** within the CI pipeline to ensure the EKS cluster isn't provisioned with public API endpoints or unencrypted EBS volumes.
2. **OpenTofu Migration:** Due to Terraform's licensing changes, 2026 DevSecOps standards heavily favor **OpenTofu** as the open-source, drop-in replacement for Terraform to maintain vendor neutrality and community-driven governance.

