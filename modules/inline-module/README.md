<!-- BEGIN_TF_DOCS -->
### Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.3 |
| <a name="requirement_equinix"></a> [equinix](#requirement\_equinix) | >= 1.8.0 |

### Providers

| Name | Version |
|------|---------|
| <a name="provider_equinix"></a> [equinix](#provider\_equinix) | >= 1.8.0 |

### Modules

No modules.

### Resources

| Name | Type |
|------|------|
| [equinix_metal_gateway.inline_module_gateway](https://registry.terraform.io/providers/equinix/equinix/latest/docs/resources/metal_gateway) | resource |
| [equinix_metal_vlan.inline_module_vlan](https://registry.terraform.io/providers/equinix/equinix/latest/docs/resources/metal_vlan) | resource |

### Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_inline_module_project_id"></a> [inline\_module\_project\_id](#input\_inline\_module\_project\_id) | The example project id value defines what will be included in the example resource in main.tf. This example is descriptive. | `string` | n/a | yes |

### Outputs

| Name | Description |
|------|-------------|
| <a name="output_metal_gateway_id"></a> [metal\_gateway\_id](#output\_metal\_gateway\_id) | The example output. In practice, output value reference implicit resource attributes declared in main.tf |
<!-- END_TF_DOCS -->