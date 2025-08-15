Pi-Cluster Kubernetes HomeLab
A GitOps-managed Kubernetes cluster running on Raspberry Pi hardware with Flux CD, SOPS encryption, and local-only services.
🏗️ Infrastructure

Hardware: Raspberry Pi cluster
Kubernetes: k3s distribution
GitOps: Flux CD for automated deployments
Secrets: SOPS with age encryption
Ingress: Traefik with custom domains
DNS: Cloudflare DNS (local resolution)

🚀 Deployed Services

Grafana: grafana.alexsantiago.net - Monitoring dashboards
Linkding: lds.alexsantiago.net - Bookmark management
Prometheus: Metrics collection and alerting

🔒 Security

Local Network Only: Services accessible only from internal network
HTTPS: Self-signed TLS certificates for all services
Encrypted Secrets: All sensitive data encrypted with SOPS
GitOps: Infrastructure as code with version control

📁 Repository Structure
├── apps/                    # Application deployments
├── clusters/staging/        # Cluster configuration
├── monitoring/             # Prometheus & Grafana stack
│   ├── controllers/        # Monitoring controllers
│   └── configs/           # Monitoring configurations
└── flux-system/           # Flux CD system components
🛠️ Key Technologies

k3s - Lightweight Kubernetes
Flux CD - GitOps continuous delivery
SOPS - Secrets encryption
Traefik - Ingress controller
Helm - Package management
Prometheus/Grafana - Monitoring stack

🎯 Features
✅ Automated deployments via Git
✅ Encrypted secrets in public repo
✅ Custom domain names with HTTPS
✅ Complete monitoring stack
✅ Local-only network security
✅ Infrastructure as code
