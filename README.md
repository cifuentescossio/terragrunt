# Terragrunt

## What is Terragrunt

Terragrunt is a tool that works with Terraform to make managing infrastructure easier. It is very effective for complex infrastructure and helps manage deployments across different environments.

The problems that Terragrunt solves are:

1. Configuration Complexity
2. Remote State Management Challenges
3. Code duplication
4. Consistency Across Platforms
5. Collaboration and versioning

### Terragrunt Features

* Hierarchical Configuration - Organize your infrastructure code in a clear structure
* Remote State Management - Easily manage where Terraform stores its state files
* Modular Variable Definitions - Share variables across different environments
* DRY (Don't Repeat Yourself) Approach - Write code once and reuse it

### Terragrunt/Terraform Versions Compatibility

Terragrunt has a compatibility table that shows which version works with Terraform or OpenTofu. It is important to check this before installing.

Reference link: https://terragrunt.gruntwork.io/docs/reference/supported-versions/

### Terragrunt  Cache

Terragrunt relies in .terragerunt-cache for operations where it download modules and providers

## Installing Terragrunt

To install Terragrunt on macOS, use Homebrew:

```bash
brew install terragrunt
```

For other installation methods, check the documentation: https://terragrunt.gruntwork.io/docs/getting-started/install/

To check if the installation was successful, run:

```bash
terragrunt --version
```