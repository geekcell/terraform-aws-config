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

- resource.aws_config_config_rule.autoscaling_group_elb_healthcheck_required (modules/rules/ec2/autoscaling_group_elb_healthcheck_required.tf#1)
- resource.aws_config_config_rule.ec2_volume_in_use (modules/rules/ec2/ebs_volume_in_use.tf#1)
- resource.aws_config_config_rule.encrypted_volumes (modules/rules/ec2/encrypted_volumes.tf#1)
- resource.aws_config_config_rule.instances_in_vpc (modules/rules/ec2/instances_in_vpc.tf#1)
<!-- END_TF_DOCS -->
