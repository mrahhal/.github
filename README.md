# .github

Contains shared GitHub assets for my projects.

## Workflows

### [ci-dotnet-package.yml](.github/workflows/ci-dotnet-package.yml)

This workflow assumes the existence of the following in the caller repo:

- script.ps1
- version.props

Template repo references:

- https://github.com/mrahhal/template-dotnet-package
- https://github.com/mrahhal/template-roslyn-analyzer

### [ci-node-package-lerna.yml](.github/workflows/ci-node-package-lerna.yml)

Template repo references:

- https://github.com/mrahhal/template-angular-package
