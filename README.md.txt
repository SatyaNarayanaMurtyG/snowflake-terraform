# Snowflake Terraform Automation

This repo demonstrates how to:
1. Use Snowflake Cortex + Snowpark to convert user requests into Terraform templates.
2. Store Terraform templates inside Snowflake.
3. Execute Terraform via Snowpark (Python subprocess).

## Folder Structure
- `terraform/` → Base Terraform provider + generated resources
- `snowpark/` → Python automation scripts
- `sql/` → SQL rules and governance tables

## How to Run
```bash
cd terraform
terraform init
terraform apply
