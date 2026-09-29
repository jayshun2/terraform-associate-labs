# Terraform Associate 004 labs

Public labs for a free YouTube series that prepares you for the HashiCorp Terraform Associate (004) exam, which tests Terraform 1.12.

This is exam prep, not exam dumps. There are no leaked questions here and there never will be.

## Official exam content

Study against HashiCorp's own objective list, not this repo:

- [Terraform Associate (004) review / content list](https://developer.hashicorp.com/terraform/tutorials/certification-004/associate-review-004)
- [Terraform Associate (004) certification tutorials](https://developer.hashicorp.com/terraform/tutorials/certification-004)
- [HashiCorp infrastructure automation certifications](https://developer.hashicorp.com/certifications/infrastructure-automation)

## Providers

Labs may use the `hashicorp/aws`, `hashicorp/random`, and `hashicorp/local` providers. AWS is only the lab vehicle. The exam itself is provider-agnostic.

You bring your own AWS account. This repo does not hand out keys.

## Rules for this repo

- No credentials or keys are committed. Ever.
- No Terraform state is committed. See `.gitignore`.
- Every lab must be destroyable with one `terraform destroy`.

## Layout

One folder per video. Video 14 (exam day) has no lab folder.

| Folder | Video |
|---|---|
| `01-iac/` | What IaC is, and what Terraform is not |
| `02-providers/` | Providers, versions, lock file |
| `03-state/` | State: the part tutorials skip |
| `04-workflow/` | Workflow: init validate plan apply destroy fmt |
| `05-resources-data/` | Resources vs data sources |
| `06-variables-outputs/` | Variables, outputs, complex types |
| `07-expressions/` | Expressions, functions, count/for_each |
| `08-lifecycle-conditions/` | Lifecycle, depends_on, conditions |
| `09-sensitive-ephemeral/` | Sensitive data, ephemeral, write-only |
| `10-modules/` | Modules: source, version, scope |
| `11-remote-state/` | Remote state and locking |
| `12-drift-import/` | Drift, import, inspect, TF_LOG |
| `13-hcp/` | HCP Terraform: runs, workspaces, projects, governance |

The folders are a skeleton right now. Lab code lands after each video outline is final.
