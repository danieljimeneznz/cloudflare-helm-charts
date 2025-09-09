# Cloudflare Helm Charts

### About
A convenient location to publish Cloudflare helm charts

### Setup
```bash
helm repo add cloudflare https://danieljimeneznz.github.io/cloudflare-helm-charts
helm repo update
```

### Discovery
```bash
helm search repo cloudflare
```

### Contents

- `charts/cloudflare-tunnel`: Helm 3 chart using cloudflared best practices
- `charts/cloudflare-tunnel-remote`: Helm 3 chart for a remotely configured cloudflared tunnel
