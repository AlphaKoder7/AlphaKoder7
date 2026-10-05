<p align="center">
  <img src="https://github.com/AlphaKoder7/Doctor_Appointment_System/blob/main/images/%C2%ABCLOUDS%C2%BB%202D%20VFX%20Animation,%20Ivan%20Boyko.gif?raw=true" alt="Cloud Animation Banner" width="100%" height="200px" />
</p>

## Hi, I'm Abin 👋

🎓 Completed my M.Sc. Computer Applications studies at SICSR Pune (2026) <br>
☁️ Focused on DevOps, SRE, Platform Engineering and Cloud Infrastructure <br>
🔧 I build infrastructure and delivery automation on AWS and Azure with Terraform, Ansible, Python and GitHub Actions <br>
🐳 Hands-on projects with Docker, Kubernetes, Helm, Linux operations and observability <br>
📜 Currently pursuing AZ-104: Microsoft Azure Administrator <br>
📍 Bengaluru · Open to relocation · Available immediately

## 🚀 Projects

### [DevOps Lab — AWS Application Delivery](https://github.com/AlphaKoder7/Devops-Lab)

Completed application delivery lab that takes a FastAPI service from a Git push through automated tests, Docker image publishing and deployment to K3s on AWS.

- Terraform provisions networking, EC2 and IAM; GitHub Actions deploys commit-tagged GHCR images with Helm through AWS Systems Manager using OIDC.
- Prometheus metrics and alert rules, Grafana dashboards and Kubernetes health checks support deployment monitoring.

**Stack:** AWS · Terraform · Docker · Kubernetes / K3s · Helm · GitHub Actions · Prometheus · Grafana

### [Phoenix Protocol — Azure SQL Validation Automation](https://github.com/AlphaKoder7/Phoenix-Protocol)

Scheduled validation pipeline that provisions temporary Azure SQL infrastructure, copies a source database, runs SQL checks and tears down the drill environment.

- Python and the Azure SDK orchestrate database copying and table-count or targeted row-count checks.
- GitHub Actions supports weekly and manual drills with Service Principal authentication and cleanup configured to run even after an earlier failure.

**Stack:** Azure SQL · Terraform · Python · Azure SDK · pyodbc · GitHub Actions

### [FleetOps — Linux Fleet Operations](https://github.com/AlphaKoder7/FleetOps)

Ansible automation for three local Ubuntu VMs: one HAProxy load balancer and two application servers. Local implementation and validation are complete.

- Detects and repairs managed configuration drift; performs health-gated rolling package upgrades and reboots, stopping on failure before modifying the next node.
- 25 portable tests and real-VM exercises passed. The recorded local upgrade and reboot run sampled 678 HTTP requests with no observed failures and 4.74 ms p95 latency.

**Stack:** Ansible · Linux · Python · HAProxy · systemd · KVM / libvirt · cloud-init

[Validation evidence](https://github.com/AlphaKoder7/FleetOps/tree/main/evidence) · AWS deployment remains a future extension.

### [Simulation Job Queue API — API & Observability](https://github.com/AlphaKoder7/Simulation-job-Queue)

Containerised FastAPI service that simulates job processing with validated requests, background lifecycle transitions and application metrics.

- Submit and inspect jobs as they move from pending to running to completed; Docker Compose runs the API, Prometheus and Grafana together.
- Health checks, interactive API documentation, pytest and GitHub Actions support inspection and testing. Job state is stored in memory.

**Stack:** FastAPI · Python · Pydantic · Docker Compose · Prometheus · Grafana · pytest · GitHub Actions

<div align="center">

<h2>💻 Tech Stack</h2>

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge" alt="AWS" />
  <img src="https://img.shields.io/badge/Azure-0072C6?style=for-the-badge" alt="Azure" />
  <img src="https://img.shields.io/badge/Terraform-5835CC?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Ansible" />
</p>
<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Docker-0DB7ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm" />
</p>
<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/HAProxy-213B55?style=for-the-badge" alt="HAProxy" />
</p>
<p>
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=FFDD54" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Bash" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
  <img src="https://img.shields.io/badge/Git-F05033?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
</p>

<h2>🔗 Find Me</h2>

<a href="https://alphakoder7.github.io/"><img src="https://img.shields.io/badge/Portfolio-1A1F36?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/abin-issac-cloud"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge" alt="LinkedIn" /></a>
<a href="mailto:abin.issac2001@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

</div>
