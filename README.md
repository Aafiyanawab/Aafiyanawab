<div align="center">

# Aafiya Nawab 👋
### Cloud/DevOps Engineer (Fresher)
Building and deploying cloud-native infrastructure — AWS · Terraform · Docker · Kubernetes · CI/CD

[LinkedIn](https://www.linkedin.com/in/aafiyanawab-7b66822b9) · [Email](mailto:aafiyanawab@gmail.com)

---

## About

I build cloud infrastructure end-to-end — provisioning with Terraform, containerizing with Docker, deploying on Kubernetes, and wiring in CI/CD so releases ship without manual babysitting. During my internship I automated IAM workflows and cost-management alerting on AWS. On my own, I've designed and deployed three complete systems spanning AI-powered platforms, zero-downtime deployment pipelines, and serverless data processing.

**75% reduction in AWS Comprehend API calls**  ·  **Zero-downtime Blue-Green deployments**  ·  **Zero SSH keys in CI/CD (OIDC-based auth)**  ·  **Automated IAM workflows in production**

---

## Tech Stack

| | |
|---|---|
| **Cloud** | AWS — EC2, ECS/Fargate, EKS, Lambda, S3, IAM, VPC, RDS, ECR, Route 53, API Gateway, WAF, CloudWatch; familiar with Azure, GCP |
| **IaC** | Terraform (modules, remote state) |
| **Containers** | Docker, Kubernetes (k3s) |
| **CI/CD** | GitHub Actions (OIDC, SSM), Jenkins, Git |
| **Observability** | Prometheus, Grafana, CloudWatch |
| **Security scanning** | CodeQL, Trivy, SonarQube, Dependabot |
| **Scripting** | Python (Boto3, Flask), Bash/Shell(Basic) |
| **Databases** | PostgreSQL, DynamoDB, MongoDB, MySQL |
| **OS & Networking** | Linux, TCP/IP, DNS, HTTP/HTTPS, SSH, Firewalls |

---

## Projects

**🔹 ContextFlow – AI-Powered Repository Intelligence Platform**
`Python` `Flask` `PostgreSQL` `Docker` `Kubernetes` `AWS` `Terraform` `Prometheus` `Grafana`
Live, repository-aware AI chat platform with an Intent Engine, Context Builder, and Semantic Cache that reduces redundant OpenAI API calls. Deployed on a Terraform-provisioned k3s cluster with a credential-free GitHub Actions → OIDC → ECR CI/CD pipeline, DevSecOps scanning (CodeQL, Trivy, Dependabot), and Prometheus/Grafana monitoring.
🔗 Live Demo · GitHub

**🔹 Blue-Green Deployment Pipeline on AWS ECS Fargate**
`Jenkins` `Docker` `Terraform` `AWS ECS` `ALB`
Zero-downtime releases via automated Blue-Green traffic switching on ECS Fargate, gated by an 8-test Jest/Supertest quality check before every Docker image build. Full infrastructure (VPC, ALB, ECS, ECR, IAM) provisioned end-to-end with Terraform.
🔗 GitHub

**🔹 Customer Review Analyser**
`Python` `Flask` `AWS Comprehend` `Docker`
Serverless sentiment-analysis platform processing bulk CSV/Excel review uploads. Cut AWS Comprehend API calls by 75% via an event-driven S3 → Lambda → Comprehend Batch pipeline. Interactive dashboard (charts, key-phrase extraction, entity detection) with login-free, isolated sessions and automatic 24-hour TTL cleanup.
🔗 Live Demo · GitHub

**🔹 Zidd 2.0 – Team Cloud Platform Deployment**
`Terraform` `AWS EKS` `IRSA` `WAF` `Microservices` — *team project*
Deployed a team-built, Terraform-defined AWS infrastructure (EKS, IRSA, WAF, microservices architecture) independently, end-to-end, on a personal AWS account. Contributed Terraform changes to the shared codebase: migrated to an S3 remote backend with DynamoDB state locking, renamed ECR repositories, removed an unused RDS instance, and right-sized EC2 resources. Core platform architecture built by teammates.

---

## Experience

**Cloud Engineer Intern** — Cloud4Green Technologies (Jan – May 2026)
Automated AWS IAM workflows with Python and IAM Identity Center, built Terraform-based Infrastructure as Code for resource provisioning, and supported AWS cost-management automation with Budgets, SNS, and Lambda.

---

## Currently learning
<!-- fill this in — e.g. Kubernetes RBAC, Helm, a specific cert you're working toward -->

---

![AWS](https://skillicons.dev/icons?i=aws,terraform,docker,kubernetes,githubactions,python,jenkins,git,linux)
