# setup-ig

A GitHub Action to install the [Inspektor Gadget](https://inspektor-gadget.io/) `ig` CLI.

## Usage

```yaml
steps:
  - uses: mqasimsarfraz/setup-ig@main
```

### Pin to a specific version

```yaml
steps:
  - uses: mqasimsarfraz/setup-ig@main
    with:
      version: "v0.51.1"
```

## Inputs

| Name      | Description                                      | Default  |
|-----------|--------------------------------------------------|----------|
| `version` | Version of ig to install (e.g. `v0.51.1`).      | `latest` |
