## Why use Terraform?

- Popular IAC Tool - Opensource

[Infrastructure As Code](./Agile/IAC.md)

- Terraform allows you to define Infrastructure for variety of providers (Azure, AWS, Google)
- Uses simple declarative programming language called HCL to deploy using variety of commands

Usually an environment would require setting up routing, internet gateways and network connections etc. Instead of configuring the environment in a manual way, we can use IAC tool.

- Terraform code - uses HCL and supports JSON syntax
- Write code to define and provision and manage the cloud infrastructure
- Means we can automate the provisioning and deployment process
- Terraform is agnostic to resource providers
- 3 main steps with Terraform:

  - Write the code in HCL (easy to read)

  - Plan - preview changes before applying
  - Create - can use same code in multiple places, Staging, Dev, QA environments. Share configuration across teams (reproducible infrastructure)
