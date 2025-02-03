<h1 align="center">Runnex</h1>
<p align="center">Runnex is a platform for running CI/CD pipelines on high-performance runners.</p>

<p align="center">
  <a href="https://runnex.dev"><b>Website</b></a> •
  <a href="https://docs.runnex.dev"><b>Documentation</b></a> •
  <a href="https://github.com/runnexdev/runnex/issues"><b>Questions</b></a> •
  <a href="https://ctrlplane.dev"><b>By Ctrlplane</b></a>
</p>

---

## Getting Started

### 1. Install the GitHub App

Head over to [runnex.dev](https://runnex.dev/login) and authenticate with your
GitHub account. Follow the installation wizard to add the Runnex GitHub App to
your organization.

### 2. Update Your Workflow Files

Modify your GitHub Actions workflow files to use Runnex's high-performance
runners by updating the `runs-on` field:

```yaml
jobs:
  build:
    runs-on: runnex-2vcpu-ubuntu-2404
    steps: ...
```
