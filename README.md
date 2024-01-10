<!-- BEGIN_TF_DOCS -->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0 |
| <a name="requirement_aws"></a> [aws](#requirement\_aws) | >= 4.64 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | >= 4.64 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_cloudwatch_event_api_destination.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_api_destination) | resource |
| [aws_cloudwatch_event_archive.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_archive) | resource |
| [aws_cloudwatch_event_bus.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_bus) | resource |
| [aws_cloudwatch_event_connection.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_connection) | resource |
| [aws_cloudwatch_event_permission.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_permission) | resource |
| [aws_cloudwatch_event_rule.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_rule) | resource |
| [aws_cloudwatch_event_rule.this_lifecycle](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_rule) | resource |
| [aws_cloudwatch_event_target.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/cloudwatch_event_target) | resource |
| [aws_iam_policy.additional_inline](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.additional_json](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.additional_jsons](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.api_destination](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.cloudwatch](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.ecs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.kinesis](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.kinesis_firehose](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.sfn](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.sns](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.sqs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy.tracing](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy_attachment.additional_inline](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.additional_json](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.additional_jsons](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.api_destination](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.cloudwatch](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.ecs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.kinesis](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.kinesis_firehose](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.sfn](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.sns](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.sqs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_policy_attachment.tracing](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy_attachment) | resource |
| [aws_iam_role.eventbridge](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role) | resource |
| [aws_iam_role_policy_attachment.additional_many](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_iam_role_policy_attachment.additional_one](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_role_policy_attachment) | resource |
| [aws_scheduler_schedule.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/scheduler_schedule) | resource |
| [aws_scheduler_schedule.this_lifecyle](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/scheduler_schedule) | resource |
| [aws_scheduler_schedule_group.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/scheduler_schedule_group) | resource |
| [aws_schemas_discoverer.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/schemas_discoverer) | resource |
| [aws_cloudwatch_event_bus.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/cloudwatch_event_bus) | data source |
| [aws_iam_policy.tracing](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy) | data source |
| [aws_iam_policy_document.additional_inline](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.api_destination](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.assume_role](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.cloudwatch](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.ecs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.kinesis](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.kinesis_firehose](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.lambda](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.sfn](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.sns](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |
| [aws_iam_policy_document.sqs](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_api_destinations"></a> [api\_destinations](#input\_api\_destinations) | A map of objects with EventBridge Destination definitions. | `map(any)` | `{}` | no |
| <a name="input_append_connection_postfix"></a> [append\_connection\_postfix](#input\_append\_connection\_postfix) | Controls whether to append '-connection' to the name of the connection | `bool` | `true` | no |
| <a name="input_append_destination_postfix"></a> [append\_destination\_postfix](#input\_append\_destination\_postfix) | Controls whether to append '-destination' to the name of the destination | `bool` | `true` | no |
| <a name="input_append_rule_postfix"></a> [append\_rule\_postfix](#input\_append\_rule\_postfix) | Controls whether to append '-rule' to the name of the rule | `bool` | `true` | no |
| <a name="input_append_schedule_group_postfix"></a> [append\_schedule\_group\_postfix](#input\_append\_schedule\_group\_postfix) | Controls whether to append '-group' to the name of the schedule group | `bool` | `true` | no |
| <a name="input_append_schedule_postfix"></a> [append\_schedule\_postfix](#input\_append\_schedule\_postfix) | Controls whether to append '-schedule' to the name of the schedule | `bool` | `true` | no |
| <a name="input_archives"></a> [archives](#input\_archives) | A map of objects with the EventBridge Archive definitions. | `map(any)` | `{}` | no |
| <a name="input_attach_api_destination_policy"></a> [attach\_api\_destination\_policy](#input\_attach\_api\_destination\_policy) | Controls whether the API Destination policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_cloudwatch_policy"></a> [attach\_cloudwatch\_policy](#input\_attach\_cloudwatch\_policy) | Controls whether the Cloudwatch policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_ecs_policy"></a> [attach\_ecs\_policy](#input\_attach\_ecs\_policy) | Controls whether the ECS policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_kinesis_firehose_policy"></a> [attach\_kinesis\_firehose\_policy](#input\_attach\_kinesis\_firehose\_policy) | Controls whether the Kinesis Firehose policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_kinesis_policy"></a> [attach\_kinesis\_policy](#input\_attach\_kinesis\_policy) | Controls whether the Kinesis policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_lambda_policy"></a> [attach\_lambda\_policy](#input\_attach\_lambda\_policy) | Controls whether the Lambda Function policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_policies"></a> [attach\_policies](#input\_attach\_policies) | Controls whether list of policies should be added to IAM role | `bool` | `false` | no |
| <a name="input_attach_policy"></a> [attach\_policy](#input\_attach\_policy) | Controls whether policy should be added to IAM role | `bool` | `false` | no |
| <a name="input_attach_policy_json"></a> [attach\_policy\_json](#input\_attach\_policy\_json) | Controls whether policy\_json should be added to IAM role | `bool` | `false` | no |
| <a name="input_attach_policy_jsons"></a> [attach\_policy\_jsons](#input\_attach\_policy\_jsons) | Controls whether policy\_jsons should be added to IAM role | `bool` | `false` | no |
| <a name="input_attach_policy_statements"></a> [attach\_policy\_statements](#input\_attach\_policy\_statements) | Controls whether policy\_statements should be added to IAM role | `bool` | `false` | no |
| <a name="input_attach_sfn_policy"></a> [attach\_sfn\_policy](#input\_attach\_sfn\_policy) | Controls whether the StepFunction policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_sns_policy"></a> [attach\_sns\_policy](#input\_attach\_sns\_policy) | Controls whether the SNS policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_sqs_policy"></a> [attach\_sqs\_policy](#input\_attach\_sqs\_policy) | Controls whether the SQS policy should be added to IAM role for EventBridge Target | `bool` | `false` | no |
| <a name="input_attach_tracing_policy"></a> [attach\_tracing\_policy](#input\_attach\_tracing\_policy) | Controls whether X-Ray tracing policy should be added to IAM role for EventBridge | `bool` | `false` | no |
| <a name="input_aws_environment"></a> [aws\_environment](#input\_aws\_environment) | Aws environment | `string` | n/a | yes |
| <a name="input_bus_name"></a> [bus\_name](#input\_bus\_name) | A unique name for your EventBridge Bus | `string` | `"default"` | no |
| <a name="input_cloudwatch_target_arns"></a> [cloudwatch\_target\_arns](#input\_cloudwatch\_target\_arns) | The Amazon Resource Name (ARN) of the Cloudwatch Log Streams you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_connections"></a> [connections](#input\_connections) | A map of objects with EventBridge Connection definitions. | `any` | `{}` | no |
| <a name="input_create"></a> [create](#input\_create) | Controls whether resources should be created | `bool` | `true` | no |
| <a name="input_create_api_destinations"></a> [create\_api\_destinations](#input\_create\_api\_destinations) | Controls whether EventBridge Destination resources should be created | `bool` | `false` | no |
| <a name="input_create_archives"></a> [create\_archives](#input\_create\_archives) | Controls whether EventBridge Archive resources should be created | `bool` | `false` | no |
| <a name="input_create_bus"></a> [create\_bus](#input\_create\_bus) | Controls whether EventBridge Bus resource should be created | `bool` | `true` | no |
| <a name="input_create_connections"></a> [create\_connections](#input\_create\_connections) | Controls whether EventBridge Connection resources should be created | `bool` | `false` | no |
| <a name="input_create_permissions"></a> [create\_permissions](#input\_create\_permissions) | Controls whether EventBridge Permission resources should be created | `bool` | `true` | no |
| <a name="input_create_role"></a> [create\_role](#input\_create\_role) | Controls whether IAM roles should be created | `bool` | `true` | no |
| <a name="input_create_rules"></a> [create\_rules](#input\_create\_rules) | Controls whether EventBridge Rule resources should be created | `bool` | `true` | no |
| <a name="input_create_rules_lifecycle"></a> [create\_rules\_lifecycle](#input\_create\_rules\_lifecycle) | Controls whether EventBridge Rule with lifecycle resources should be created | `bool` | `true` | no |
| <a name="input_create_schedule_groups"></a> [create\_schedule\_groups](#input\_create\_schedule\_groups) | Controls whether EventBridge Schedule Group resources should be created | `bool` | `true` | no |
| <a name="input_create_schedules"></a> [create\_schedules](#input\_create\_schedules) | Controls whether EventBridge Schedule resources should be created | `bool` | `true` | no |
| <a name="input_create_schedules_lifecycle"></a> [create\_schedules\_lifecycle](#input\_create\_schedules\_lifecycle) | Controls whether EventBridge Schedule with lifecycle resources should be created | `bool` | `true` | no |
| <a name="input_create_schemas_discoverer"></a> [create\_schemas\_discoverer](#input\_create\_schemas\_discoverer) | Controls whether default schemas discoverer should be created | `bool` | `false` | no |
| <a name="input_create_targets"></a> [create\_targets](#input\_create\_targets) | Controls whether EventBridge Target resources should be created | `bool` | `true` | no |
| <a name="input_ecs_target_arns"></a> [ecs\_target\_arns](#input\_ecs\_target\_arns) | The Amazon Resource Name (ARN) of the AWS ECS Tasks you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_event_source_name"></a> [event\_source\_name](#input\_event\_source\_name) | The partner event source that the new event bus will be matched with. Must match name. | `string` | `null` | no |
| <a name="input_kinesis_firehose_target_arns"></a> [kinesis\_firehose\_target\_arns](#input\_kinesis\_firehose\_target\_arns) | The Amazon Resource Name (ARN) of the Kinesis Firehose Delivery Streams you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_kinesis_target_arns"></a> [kinesis\_target\_arns](#input\_kinesis\_target\_arns) | The Amazon Resource Name (ARN) of the Kinesis Streams you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_lambda_target_arns"></a> [lambda\_target\_arns](#input\_lambda\_target\_arns) | The Amazon Resource Name (ARN) of the Lambda Functions you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_number_of_policies"></a> [number\_of\_policies](#input\_number\_of\_policies) | Number of policies to attach to IAM role | `number` | `0` | no |
| <a name="input_number_of_policy_jsons"></a> [number\_of\_policy\_jsons](#input\_number\_of\_policy\_jsons) | Number of policies JSON to attach to IAM role | `number` | `0` | no |
| <a name="input_permissions"></a> [permissions](#input\_permissions) | A map of objects with EventBridge Permission definitions. | `map(any)` | `{}` | no |
| <a name="input_policies"></a> [policies](#input\_policies) | List of policy statements ARN to attach to IAM role | `list(string)` | `[]` | no |
| <a name="input_policy"></a> [policy](#input\_policy) | An additional policy document ARN to attach to IAM role | `string` | `null` | no |
| <a name="input_policy_json"></a> [policy\_json](#input\_policy\_json) | An additional policy document as JSON to attach to IAM role | `string` | `null` | no |
| <a name="input_policy_jsons"></a> [policy\_jsons](#input\_policy\_jsons) | List of additional policy documents as JSON to attach to IAM role | `list(string)` | `[]` | no |
| <a name="input_policy_statements"></a> [policy\_statements](#input\_policy\_statements) | Map of dynamic policy statements to attach to IAM role | `any` | `{}` | no |
| <a name="input_role_description"></a> [role\_description](#input\_role\_description) | Description of IAM role to use for EventBridge | `string` | `null` | no |
| <a name="input_role_force_detach_policies"></a> [role\_force\_detach\_policies](#input\_role\_force\_detach\_policies) | Specifies to force detaching any policies the IAM role has before destroying it. | `bool` | `true` | no |
| <a name="input_role_name"></a> [role\_name](#input\_role\_name) | Name of IAM role to use for EventBridge | `string` | `null` | no |
| <a name="input_role_path"></a> [role\_path](#input\_role\_path) | Path of IAM role to use for EventBridge | `string` | `null` | no |
| <a name="input_role_permissions_boundary"></a> [role\_permissions\_boundary](#input\_role\_permissions\_boundary) | The ARN of the policy that is used to set the permissions boundary for the IAM role used by EventBridge | `string` | `null` | no |
| <a name="input_role_tags"></a> [role\_tags](#input\_role\_tags) | A map of tags to assign to IAM role | `map(string)` | `{}` | no |
| <a name="input_rules"></a> [rules](#input\_rules) | A map of objects with EventBridge Rule definitions. | `map(any)` | `{}` | no |
| <a name="input_schedule_group_timeouts"></a> [schedule\_group\_timeouts](#input\_schedule\_group\_timeouts) | A map of objects with EventBridge Schedule Group create and delete timeouts. | `map(string)` | `{}` | no |
| <a name="input_schedule_groups"></a> [schedule\_groups](#input\_schedule\_groups) | A map of objects with EventBridge Schedule Group definitions. | `any` | `{}` | no |
| <a name="input_schedules"></a> [schedules](#input\_schedules) | A map of objects with EventBridge Schedule definitions. | `map(any)` | `{}` | no |
| <a name="input_schemas_discoverer_description"></a> [schemas\_discoverer\_description](#input\_schemas\_discoverer\_description) | Default schemas discoverer description | `string` | `"Auto schemas discoverer event"` | no |
| <a name="input_sfn_target_arns"></a> [sfn\_target\_arns](#input\_sfn\_target\_arns) | The Amazon Resource Name (ARN) of the StepFunctions you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_sns_target_arns"></a> [sns\_target\_arns](#input\_sns\_target\_arns) | The Amazon Resource Name (ARN) of the AWS SNS's you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_sqs_target_arns"></a> [sqs\_target\_arns](#input\_sqs\_target\_arns) | The Amazon Resource Name (ARN) of the AWS SQS Queues you want to use as EventBridge targets | `list(string)` | `[]` | no |
| <a name="input_tags"></a> [tags](#input\_tags) | A map of tags to assign to resources. | `map(string)` | `{}` | no |
| <a name="input_targets"></a> [targets](#input\_targets) | A map of objects with EventBridge Target definitions. | `any` | `{}` | no |
| <a name="input_trusted_entities"></a> [trusted\_entities](#input\_trusted\_entities) | Additional trusted entities for assuming roles (trust relationship) | `list(string)` | `[]` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_eventbridge_api_destination_arns"></a> [eventbridge\_api\_destination\_arns](#output\_eventbridge\_api\_destination\_arns) | The EventBridge API Destination ARNs |
| <a name="output_eventbridge_archive_arns"></a> [eventbridge\_archive\_arns](#output\_eventbridge\_archive\_arns) | The EventBridge Archive ARNs |
| <a name="output_eventbridge_bus_arn"></a> [eventbridge\_bus\_arn](#output\_eventbridge\_bus\_arn) | The EventBridge Bus ARN |
| <a name="output_eventbridge_bus_name"></a> [eventbridge\_bus\_name](#output\_eventbridge\_bus\_name) | The EventBridge Bus Name |
| <a name="output_eventbridge_connection_arns"></a> [eventbridge\_connection\_arns](#output\_eventbridge\_connection\_arns) | The EventBridge Connection Arns |
| <a name="output_eventbridge_connection_ids"></a> [eventbridge\_connection\_ids](#output\_eventbridge\_connection\_ids) | The EventBridge Connection IDs |
| <a name="output_eventbridge_permission_ids"></a> [eventbridge\_permission\_ids](#output\_eventbridge\_permission\_ids) | The EventBridge Permission IDs |
| <a name="output_eventbridge_role_arn"></a> [eventbridge\_role\_arn](#output\_eventbridge\_role\_arn) | The ARN of the IAM role created for EventBridge |
| <a name="output_eventbridge_role_name"></a> [eventbridge\_role\_name](#output\_eventbridge\_role\_name) | The name of the IAM role created for EventBridge |
| <a name="output_eventbridge_rule_arns"></a> [eventbridge\_rule\_arns](#output\_eventbridge\_rule\_arns) | The EventBridge Rule ARNs |
| <a name="output_eventbridge_rule_ids"></a> [eventbridge\_rule\_ids](#output\_eventbridge\_rule\_ids) | The EventBridge Rule IDs |
| <a name="output_eventbridge_schedule_arns"></a> [eventbridge\_schedule\_arns](#output\_eventbridge\_schedule\_arns) | The EventBridge Schedule ARNs created |
| <a name="output_eventbridge_schedule_group_arns"></a> [eventbridge\_schedule\_group\_arns](#output\_eventbridge\_schedule\_group\_arns) | The EventBridge Schedule Group ARNs |
| <a name="output_eventbridge_schedule_group_ids"></a> [eventbridge\_schedule\_group\_ids](#output\_eventbridge\_schedule\_group\_ids) | The EventBridge Schedule Group IDs |
| <a name="output_eventbridge_schedule_group_states"></a> [eventbridge\_schedule\_group\_states](#output\_eventbridge\_schedule\_group\_states) | The EventBridge Schedule Group states |
| <a name="output_eventbridge_schedule_ids"></a> [eventbridge\_schedule\_ids](#output\_eventbridge\_schedule\_ids) | The EventBridge Schedule IDs created |
<!-- END_TF_DOCS -->