# terraform-azurerm-resource_group_storage

Basic Terraform module for creating Azure resource group and storage

## Usage

To use this module, add the following to your Terraform configuration:

```hcl
module "azure_resources" {
  source                 = "Rozdorozhnii/resource_group_storage/azurerm"
  resource_group_name    = "example-rg"
  location               = "East US"
  storage_account_name   = "examplestoracc"
  version              = "1.0.0"
}
```

### License

This project is created for educational purposes and is licensed under the Apache 2.0 License. See the [LICENSE](./LICENSE) file for details.
