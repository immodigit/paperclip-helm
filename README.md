# Paperclip Helm Chart

Helm chart for deploying [Paperclip](https://github.com/paperclipai/paperclip) on Kubernetes.

## Usage

### Via OCI Registry

```bash
helm install paperclip oci://ghcr.io/immodigit/charts/paperclip
```

### Via Helm Repo

```bash
helm repo add immodigit https://immodigit.github.io/paperclip-helm
helm install paperclip immodigit/paperclip
```

## Features

- CNPG PostgreSQL operator integration (with pgtune)
- Barman S3 backup support
- Traefik ingress with TLS
- Configurable resource limits

## Configuration

See [values.yaml](charts/paperclip/values.yaml) for all available options.
