<!-- BEGIN_TF_DOCS -->
 # Azure Resource Group
[![Changelog](https://img.shields.io/badge/changelog-release-green.svg)](CHANGELOG.md) [![Notice](https://img.shields.io/badge/notice-copyright-yellow.svg)](NOTICE) [![Apache V2 License](https://img.shields.io/badge/license-Apache%20V2-orange.svg)](LICENSE) [![TF Registry](https://img.shields.io/badge/terraform-registry-blue.svg)](https://registry.terraform.io/modules/TheIronRock95/resourcegroup/azurerm/latest)

# Usage - Module

```hcl

```
## Providers

| Name | Version |
|------|---------|
| azurerm | >= 2.0.0 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [azurerm_resource_group.this](https://registry.terraform.io/providers/hashicorp/azurerm/latest/docs/resources/resource_group) | resource |

## Inputs

| Name | Description | Type | Required |
|------|-------------|------|:--------:|
| azure\_location | The Azure Region where the Resource Group should exist. Changing this forces a new Resource Group to be created. | `string` | yes |
| resource\_group\_name | The Name which should be used for this Resource Group. Changing this forces a new Resource Group to be created. | `list(string)` | yes |
| number\_of\_resource\_groups | Amount of resource group(s) to create for the configuration | `number` | no |
| resource\_group\_tags | A mapping of tags which should be assigned to the Resource Group. | `list(map(any))` | no |

## Outputs

| Name | Description |
|------|-------------|
| resource\_group\_id | resource group id |
| resource\_group\_location | resource group location |
| resource\_group\_name | resource group name |

## Related documentation
<!-- END_TF_DOCS -->