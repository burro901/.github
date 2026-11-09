<p align="center">
  <img src="https://raw.githubusercontent.com/krateo-platformops/krateo/main/docs/media/krateo-logo.png" width="300" alt="Krateo PlatformOps">
</p>

<p align="center">
  An open-source control plane on Kubernetes that creates and governs any resource, on any infrastructure.<br>
  Platform teams publish golden paths once; developers get a self-service portal for everything else.
</p>

## Start here

- **[krateo](https://github.com/krateo-platformops/krateo)**: what Krateo PlatformOps is, how to install it and how to get help. Start from this repository.
- **[Documentation](https://docs.krateo.io/?utm_source=github&utm_medium=org-profile&utm_campaign=krateo)**: concepts, guides and reference.
- **[krateo-blueprints](https://github.com/krateo-blueprints)**: ready-to-use blueprints for AWS, Azure, Google Cloud, OpenStack, Keycloak and more.
- **[Discussions](https://github.com/krateo-platformops/krateo/discussions)**: questions and ideas.

## Main repositories

| Repository | What it does |
|---|---|
| [installer](https://github.com/krateo-platformops/installer) | Installs the whole platform with one Helm chart, in dependency order |
| [core-provider](https://github.com/krateo-platformops/core-provider) | The composition engine: turns each blueprint into its own Kubernetes API |
| [oasgen-provider](https://github.com/krateo-platformops/oasgen-provider) | Generates a Kubernetes operator from an OpenAPI spec |
| [portal](https://github.com/krateo-platformops/portal), [frontend](https://github.com/krateo-platformops/frontend), [snowplow](https://github.com/krateo-platformops/snowplow) | The self-service portal, declared as Kubernetes resources |
| [observability](https://github.com/krateo-platformops/observability) | OpenTelemetry, ClickHouse and HyperDX for logs, metrics, traces and events |

## Looking for Krateo 3.x?

The components and tools of the Krateo 3.x release line, including `krateoctl` and the documentation sources, are in [krateoplatformops](https://github.com/krateoplatformops). Existing 3.x installations keep working from there.

## Contribute

Read [CONTRIBUTING](https://github.com/krateo-platformops/.github/blob/main/CONTRIBUTING.md) before opening a pull request, and report vulnerabilities privately as described in the [security policy](https://github.com/krateo-platformops/.github/blob/main/SECURITY.md). Krateo PlatformOps is licensed under Apache 2.0.
