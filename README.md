# Terraform Azure Resource Group Module

This module creates an Azure Resource Group.

## Usage

```hcl
module "rg" {
  source   = "git@github.com:your-org/terraform-azurerm-resource-group.git"
  name     = "my-rg"
  location = "East US"
  tags     = {
    environment = "dev"
  }
}
```