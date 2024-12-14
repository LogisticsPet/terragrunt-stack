# Deprecated. 
Description:
This repository is archived and no longer actively maintained. It serves as a reference for implementing environments using Terragrint.

Reason for Archival:
The repository is preserved to document the approach, best practices, and examples for creating infrastructure from multiple terraform modules using Terragrint. While the content is no longer updated, it may still provide valuable insights or guidance.

## Terragrunt
Terragrunt code for provisioning stack resources.
```
.
└── aws
    ├── kubernetes
    │   ├── cluster
    │   │   └── terragrunt.hcl
    │   ├── namespace
    │   │   └── core
    │   │       └── terragrunt.hcl
    │   └── tools
    │       ├── autoscaler
    │       │   └── terragrunt.hcl
    │       ├── cert_manager
    │       │   └── terragrunt.hcl
    │       ├── cert_manager_issuer
    │       │   └── terragrunt.hcl
    │       └── external_dns
    │           └── terragrunt.hcl
    ├── network
    │   ├── cloudflare_dns
    │   │   └── terragrunt.hcl
    │   ├── vpc
    │   │   └── terragrunt.hcl
    │   └── zone
    │       └── terragrunt.hcl
    └── terragrunt.hcl
```
