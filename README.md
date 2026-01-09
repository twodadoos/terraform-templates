## terraform-templates

This repository contains a collection of Terraform templates for automating the provisioning and management of infrastructure. The templates cover common use cases such as creating cloud resources, networking components, storage, and application deployments. They are designed to be modular, readable, and adaptable to different environments and cloud providers.

### **_Disclaimer_**

These Terraform templates are provided as-is for general informational and operational purposes. They reflect one possible approach based on specific assumptions, environments, cloud providers, and Terraform versions, and may not be suitable for all infrastructures. You are expected to review, understand, and test any template before applying it to your environment.

Terraform templates can create, modify, and destroy infrastructure and cloud resources. You are solely responsible for ensuring appropriate backups, safeguards, access controls, and change management practices are in place, and for validating that any template behaves as intended in your environment. No warranties are expressed or implied, and the author disclaims any liability for damages, data loss, outages, or other consequences resulting from use or misuse of these templates.  Any costs, charges, or expenses incurred from running these templates are your sole responsibility.

### **_Notes and Assumptions_**

Templates are typically designed for specific cloud providers (e.g., AWS, Azure, GCP); review provider blocks before use.

Terraform versions, provider versions, and environment-specific constraints may affect behavior.

Variables, state management, and backend configuration should be customized for your environment.

All templates are examples and may require modification to suit production use.

### Quick Start

#### Clone the repository

```
git clone https://github.com/twodadoos/Terraform-Templates.git

cd terraform-templates
```

#### Initialize Terraform in a template directory
```
cd templates/example-template

terraform init
```

#### Preview changes (plan)
```
terraform plan
```
#### Apply the template
```
terraform apply
```