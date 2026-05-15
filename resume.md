# Amr Saad EL-zoghby

amr.s.elzoghby@gmail.com | +20 109 008 0358  
[Portfolio: d2u3ifcyc2tvxh.cloudfront.net](https://d2u3ifcyc2tvxh.cloudfront.net) | [github.com/amr-elzoghby](https://github.com/amr-elzoghby)

---

## Summary

Passionately and fast-learning Junior DevOps Engineer with hands-on experience designing production-grade cloud infrastructure, container orchestration, and CI/CD automation. Built and deployed a scalable microservices platform on AWS EKS capable of handling 15,000+ concurrent users. Focused on deeply understanding system fundamentals — not just utilizing tools. Self-taught with a strong drive for continuous learning and real-world problem-solving.

---

## Skills

| Category | Technologies |
|---|---|
| **Cloud** | AWS (VPC, EKS, ECR, S3, IAM, CloudFront, Secrets Manager, SSM) |
| **Containers & Orchestration** | Docker, Kubernetes (EKS, HPA, Cluster Autoscaler), Helm |
| **IaC & Automation** | Terraform (Modular Architecture), GitHub Actions (OIDC), ArgoCD (GitOps), Bash Scripting |
| **Observability** | Prometheus, Grafana, Loki, Promtail, ServiceMonitors |
| **Web Servers & Proxies** | NGINX (Reverse Proxy, Ingress Controller) |
| **Programming** | Python |
| **Soft Skills** | Communication, Problem-Solving, Forward Thinking |
| **Languages** | Arabic (Native), English (Intermediate — B1) |

---

## Projects

### ShopScale — High-Scale E-Commerce Microservices Platform
**GitHub:** [github.com/amr-elzoghby/High-Scale-Ecommerce-K8s-15K-Concurrent](https://github.com/amr-elzoghby/High-Scale-Ecommerce-K8s-15K-Concurrent)

- Architected a production-grade e-commerce platform with **5 Node.js microservices** (User, Catalog, Cart, Order, Payment) on **AWS EKS**.
- Designed modular Terraform IaC with **isolated state layers** (Network → Storage → EKS), eliminating blast-radius risk across environments.
- Replaced NAT Gateway with **6 VPC Endpoints** (EKS, EC2, ECR, S3, STS, SSM), saving ~$32/month while keeping nodes fully private.
- Configured **HPA** (2→20 pods/service at 60% CPU) + **Cluster Autoscaler** (up to 20 Spot nodes) — load-tested to handle **15,000+ concurrent users**.
- Deployed full observability stack via Helm: **Prometheus, Grafana, Loki** with auto-configured ServiceMonitors for all microservices.
- Built CI pipeline with **GitHub Actions + OIDC** federation — zero stored AWS credentials, multi-stage Docker builds, ECR scan-on-push.
- Engineered a **GitOps** workflow using **ArgoCD** and a dual-repository strategy for automated, zero-touch Kubernetes deployments.
- Implemented **IRSA (IAM Roles for Service Accounts)** to provide pods with fine-grained, least-privilege AWS permissions (S3, Secrets Manager, STS) via OIDC provider, eliminating the need for broad node-level IAM roles.
- Implemented workload isolation: microservices on **Spot** nodes (cost-optimized), databases on **On-Demand** nodes (stability-first) using StatefulSets.

### Personal Portfolio Infrastructure
**Live:** [d2u3ifcyc2tvxh.cloudfront.net](https://d2u3ifcyc2tvxh.cloudfront.net) | **GitHub:** [github.com/amr-elzoghby/portfolio](https://github.com/amr-elzoghby/portfolio)

- Deployed a personal portfolio website on AWS using Terraform-managed infrastructure.
- Configured **S3 static hosting** with **CloudFront CDN** for global low-latency delivery and HTTPS termination.
- Automated deployments via **GitHub Actions** with OIDC-based AWS authentication — no stored secrets.

---

## Certifications & Courses

**CS50: Introduction to Computer Science — Harvard University**
- *Currently Enrolled*
- Deepening understanding of core computer science fundamentals, data structures, and low-level system operations to build a solid "under the hood" engineering foundation.

**Forward Thinking — McKinsey & Company**
- *Currently Enrolled (Week 3 of 10)*
- Professional development program focused on structured problem-solving, communication, and strategic thinking.

**Machine Learning Specialization — DeepLearning.AI & Stanford University (by Andrew Ng)**
- Completed the comprehensive 3-course specialization covering Supervised Machine Learning, Advanced Learning Algorithms (Neural Networks), and Unsupervised Learning & Recommender Systems.

---

## Education

**General Secondary Education**
*Expected Graduation: 2030*
