# Pi-Cluster Kubernetes HomeLab

A GitOps-managed Kubernetes cluster running on Raspberry Pi hardware with Flux CD, SOPS encryption, and local-only services.

## 🏗️ Infrastructure

- **Hardware**: Raspberry Pi cluster
- **Kubernetes**: k3s distribution
- **GitOps**: Flux CD for automated deployments
- **Secrets**: SOPS with age encryption
- **Ingress**: Traefik with custom domains
- **DNS**: Cloudflare DNS (local resolution)

## 🚀 Deployed Services

- **Grafana**: `grafana.alexsantiago.net` - Monitoring dashboards
- **Linkding**: `lds.alexsantiago.net` - Bookmark management
- **Prometheus**: Metrics collection and alerting

## 🔒 Security

- **Local Network Only**: Services accessible only from internal network
- **HTTPS**: Self-signed TLS certificates for all services
- **Encrypted Secrets**: All sensitive data encrypted with SOPS
- **GitOps**: Infrastructure as code with version control

## 📁 Repository Structure
