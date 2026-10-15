# Obinna Iheanacho

**DevOps / SRE Engineer** · Ontario, Canada

I build and operate cloud infrastructure, covering AWS, Kubernetes, Terraform, CI/CD, and the observability that catches problems before users notice them.

Currently open to remote SRE, Platform, Cloud and DevOps roles in Canada.

[LinkedIn](https://www.linkedin.com/in/obinna-iheanacho/) ·
[Blog](https://dev-acho.hashnode.dev) ·
[iheanachocharlie@gmail.com](mailto:iheanachocharlie@gmail.com)

---

## Stack

| | |
|---|---|
| **Cloud** | AWS — EKS, EC2, RDS, VPC, IAM, Route 53, KMS, SSM, ECR |
| **Containers** | Kubernetes (kubeadm, EKS), Docker, Helm |
| **Infrastructure as Code** | Terraform, Ansible |
| **CI/CD & GitOps** | GitHub Actions, Argo CD, Argo Rollouts, Jenkins |
| **Observability** | Prometheus, Grafana, kube-prometheus-stack, CloudWatch |
| **Supply chain security** | Trivy, Semgrep, Gitleaks, Cosign, Kyverno, SBOM |
| **Scripting** | Bash, Python, Linux |

---

## Projects

**[Robot Shop on AWS EKS](https://github.com/charliepoker/REPO)**
Production-grade EKS platform built with Terraform, featuring a VPC, Karpenter autoscaling, RDS, ACM, and KMS. CI/CD runs in GitHub Actions authenticating via OIDC with no static credentials, security gates surfaced in code scanning, signed images with SBOM attestation, and GitOps delivery through Argo CD with analysis-gated canary releases.

**[Raspberry Pi Kubernetes Homelab](https://github.com/charliepoker/k8s-raspberrypi-homelab)**
Three-node ARM64 cluster on kubeadm running WordPress, Podinfo, and a full observability
stack. Gateway API with Let's Encrypt TLS via DNS-01, Kyverno admission policies, and
eight production-layer failure modes debugged and documented.

**[Craftista Multi-Environment AWS Infrastructure](https://github.com/charliepoker/REPO)**
Terraform modules provisioning dev, staging, and prod EKS clusters across three AZs.
Three-tier VPC, keyless EC2 access via SSM, multi-AZ RDS, and per-environment budgets
with tiered alerting.

---

## Writing

I document my builds and share the parts that break at
[dev-acho.hashnode.dev](https://dev-acho.hashnode.dev).

---

## Currently

- Preparing for the CKA
- Open to remote SRE, Platform, and DevOps roles. Reach me at the email abov
