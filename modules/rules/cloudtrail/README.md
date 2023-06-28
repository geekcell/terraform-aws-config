<!-- BEGIN_TF_DOCS -->


## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_configuration"></a> [configuration](#input\_configuration) | The configurations to apply. | <pre>map(object({<br>    enabled   = bool<br>    bucket_id = optional(string)<br>  }))</pre> | n/a | yes |
| <a name="input_tags"></a> [tags](#input\_tags) | A map of tags to add to this config resource. | `map(string)` | `{}` | no |

## Outputs

No outputs.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | >= 4.4 |

## Resources

- resource.aws_config_config_rule.cloudtrail_enabled (modules/rules/cloudtrail/cloudtrail_enabled.tf#1)
- resource.aws_config_config_rule.cloudtrail_log_file_validation_enabled (modules/rules/cloudtrail/cloudtrail_log_file_validation_enabled.tf#1)
<!-- END_TF_DOCS -->
