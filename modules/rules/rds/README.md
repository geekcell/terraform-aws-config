<!-- BEGIN_TF_DOCS -->


## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_configuration"></a> [configuration](#input\_configuration) | The configurations to apply. | <pre>map(object({<br>    enabled = bool<br>  }))</pre> | n/a | yes |
| <a name="input_tags"></a> [tags](#input\_tags) | A map of tags to add to this config resource. | `map(string)` | `{}` | no |

## Outputs

No outputs.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | >= 4.4 |

## Resources

- resource.aws_config_config_rule.db_instance_backup_enabled (modules/rules/rds/db_instance_backup_enabled.tf#1)
- resource.aws_config_config_rule.rds_instance_public_access_check (modules/rules/rds/rds_instance_public_access_check.tf#1)
- resource.aws_config_config_rule.rds_multi_az_support (modules/rules/rds/rds_multi_az_support.tf#1)
- resource.aws_config_config_rule.rds_snapshots_public_prohibited (modules/rules/rds/rds_snapshots_public_prohibited.tf#1)
- resource.aws_config_config_rule.rds_storage_encrypted (modules/rules/rds/rds_storage_encrypted.tf#1)
<!-- END_TF_DOCS -->
