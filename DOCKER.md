# RepartoIT Docker images (public)

Images are built from the private RepartoIT-SIEM repository and published to GHCR.

## Pull latest (no auth)

```bash
docker pull ghcr.io/sim1andr3/repartoit-siem-collector:latest
docker pull ghcr.io/sim1andr3/repartoit-siem-dashboard:latest
docker pull ghcr.io/sim1andr3/repartoit-metrics-collector:latest
docker pull ghcr.io/sim1andr3/repartoit-iac-ingest:latest
```

## Tagged release (v0.1.28)

```bash
export REPARTOIT_IMAGE_TAG=v0.1.28
docker pull ghcr.io/sim1andr3/repartoit-siem-collector:${REPARTOIT_IMAGE_TAG}
```

Image manifest: https://github.com/sim1andr3/RepartoIT/releases/latest/download/docker-manifest.json
