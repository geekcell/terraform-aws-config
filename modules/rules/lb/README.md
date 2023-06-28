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

- resource.aws_config_config_rule.alb_http_to_https_redirection_check (modules/rules/lb/alb_http_to_https_redirection_check.tf#1)
- resource.aws_config_config_rule.elb_acm_certificate_required (modules/rules/lb/elb_acm_certificate_required.tf#1)
<!-- END_TF_DOCS -->
