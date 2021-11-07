<!-- BEGINNING OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
## Requirements

| Name | Version |
|------|---------|
| aws | ~> 3.64.2 |

## Providers

| Name | Version |
|------|---------|
| aws | ~> 3.64.2 |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| availability\_zones | Select subnets only in the given AZs | `set(string)` | `[]` | no |
| vpc\_name | The name of the VPC | `string` | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| dns\_hostnames\_enabled | Indicates if instances launched in this VPC will have public DNS hostnames |
| dns\_support\_enabled | Indicates if DNS support is enabled for this VPC |
| private\_subnets | List of private subnets in this VPC |
| public\_subnets | List of public subnets in this VPC |
| vpc\_arn | Arn of this VPC |
| vpc\_cidr\_block | CIDR range for this VPC |
| vpc\_id | The ID of the VPC |

<!-- END OF PRE-COMMIT-TERRAFORM DOCS HOOK -->
