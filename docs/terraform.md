## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_helm"></a> [helm](#provider\_helm) | n/a |
| <a name="provider_kubernetes"></a> [kubernetes](#provider\_kubernetes) | n/a |
| <a name="provider_null"></a> [null](#provider\_null) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [helm_release.app_release](https://registry.terraform.io/providers/hashicorp/helm/latest/docs/resources/release) | resource |
| [helm_release.app_release_oci](https://registry.terraform.io/providers/hashicorp/helm/latest/docs/resources/release) | resource |
| [null_resource.helm_init_oci](https://registry.terraform.io/providers/hashicorp/null/latest/docs/resources/resource) | resource |
| [kubernetes_namespace.release_ns](https://registry.terraform.io/providers/hashicorp/kubernetes/latest/docs/data-sources/namespace) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_chart_name"></a> [chart\_name](#input\_chart\_name) | n/a | `string` | n/a | yes |
| <a name="input_chart_version"></a> [chart\_version](#input\_chart\_version) | n/a | `string` | n/a | yes |
| <a name="input_helm_repo"></a> [helm\_repo](#input\_helm\_repo) | n/a | `string` | n/a | yes |
| <a name="input_inputs"></a> [inputs](#input\_inputs) | n/a | `list(any)` | `[]` | no |
| <a name="input_namespace"></a> [namespace](#input\_namespace) | # (c) 2021 - Cloud Ops Works LLC - https://cloudops.works/ On GitHub: https://github.com/cloudopsworks Distributed Under Apache v2.0 License | `string` | `"default"` | no |
| <a name="input_oci_repo"></a> [oci\_repo](#input\_oci\_repo) | n/a | `bool` | `false` | no |
| <a name="input_release_name"></a> [release\_name](#input\_release\_name) | n/a | `string` | n/a | yes |
| <a name="input_secrets"></a> [secrets](#input\_secrets) | n/a | `list(any)` | `[]` | no |
| <a name="input_var_files"></a> [var\_files](#input\_var\_files) | n/a | `list(string)` | `[]` | no |
| <a name="input_vars"></a> [vars](#input\_vars) | n/a | `map(string)` | `{}` | no |

## Outputs

No outputs.
