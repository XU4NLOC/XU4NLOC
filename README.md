# Le Xuan Loc

### DevOps / Cloud Engineer · Backend-leaning Software Engineer

I build and operate software systems where application code meets infrastructure.

My current focus is **DevOps, cloud engineering, automation, and containerized deployment**, backed by hands-on experience with Linux systems and backend development. I care about making delivery **repeatable, observable, and less dependent on manual steps**.

[LinkedIn](https://www.linkedin.com/in/le-xuanloc) · [GitHub](https://github.com/XU4NLOC) · [Email](mailto:lexuanloc0501.work@gmail.com)

---

## What I work on

- **Automation** — CI/CD workflows, scripting, validation, deployment automation
- **Cloud** — GCP, Cloud Run, Cloud Storage, Firebase, AWS
- **Containers & Linux** — Docker, Docker Compose, Incus, Ubuntu, systemd, Nginx
- **Backend systems** — Go, Python, APIs, WebSockets, PostgreSQL
- **Engineering operations** — health checks, reproducible environments, service management, failure handling

> **Current direction:** DevOps / Cloud, with backend engineering as the software layer behind the infrastructure.

---

## Selected work

### Automated Code Delivery
**Dision Tech LLC · Full-Stack Engineer · Jul 2026 – Sep 2026**

Built a Bash-based automation pipeline connecting **Gitea** with an AI coding agent for issue triage, branch creation, and pull-request generation.

**Highlights**
- Automated labeling and Git validation
- Added build verification and failure handling
- Kept **human review as the final merge gate**
- Deployed the website, automation service, and preview environments on Ubuntu + Incus
- Managed systemd services, Nginx, health checks, and scheduled snapshots

`Bash` `Gitea` `Ubuntu` `Incus` `systemd` `Nginx`

---

### Cloud Microservice Deployment
**RMIT University Vietnam × NextWay Technology · Backend Engineer (DevOps) · Mar 2025 – Sep 2025**

Supported deployment of a **7-service microservices application** on **GCP Cloud Run**, using REST-based service communication.

**Highlights**
- Automated build and deployment with GitHub Actions + Google Cloud Build
- Containerized services with Docker
- Integrated Firebase and Google Cloud Storage
- Standardized local and cloud environments

`GCP` `Cloud Run` `Docker` `GitHub Actions` `Cloud Build` `Firebase`

---

### Repeatable Containerized Delivery
**Chemizol · Software Engineer · Dec 2025 – Apr 2026**

Built a responsive React catalog covering **200+ chemical products** and established a repeatable deployment workflow for testing and stakeholder review.

`React` `Docker` `Deployment`

---

## Projects

| Project | What it demonstrates |
| --- | --- |
| [Chat Server](https://github.com/XU4NLOC/chat-server) | Concurrent Go backend, WebSockets, JWT authentication, PostgreSQL message history, Docker |
| [Port Scanner](https://github.com/XU4NLOC/portscanner) | Go concurrency, worker pools, `sync.WaitGroup`, configurable TCP scanning |

### Chat Server

A real-time backend built around a concurrent Hub architecture, with dedicated read/write goroutines per WebSocket connection.

- Authentication before the WebSocket handshake
- bcrypt password hashing
- PostgreSQL-backed message-history replay
- Dockerized development/runtime environment

**Stack:** `Go` `PostgreSQL` `WebSocket` `JWT` `Docker`

### Port Scanner

A concurrent TCP port scanner using a worker-pool model.

- Configurable host, port range, worker count, and timeout
- Reduced a 1,024-port scan from roughly **100 seconds to under 2 seconds** versus sequential scanning

**Stack:** `Go` `goroutines` `sync.WaitGroup`

---

## Technical stack

### Infrastructure
![Linux](https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-111827?style=flat-square&logo=gnubash&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-111827?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-111827?style=flat-square&logo=nginx&logoColor=white)
![systemd](https://img.shields.io/badge/systemd-111827?style=flat-square&logo=systemd&logoColor=white)
![Incus](https://img.shields.io/badge/Incus-111827?style=flat-square&logo=lxc&logoColor=white)

### CI/CD & Automation
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-111827?style=flat-square&logo=githubactions&logoColor=white)
![Google Cloud Build](https://img.shields.io/badge/Cloud%20Build-111827?style=flat-square&logo=googlecloud&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-111827?style=flat-square&logo=gitea&logoColor=white)

### Cloud
![GCP](https://img.shields.io/badge/GCP-111827?style=flat-square&logo=googlecloud&logoColor=white)
![Cloud Run](https://img.shields.io/badge/Cloud%20Run-111827?style=flat-square&logo=googlecloud&logoColor=white)
![Google Cloud Storage](https://img.shields.io/badge/Cloud%20Storage-111827?style=flat-square&logo=googlecloud&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-111827?style=flat-square&logo=firebase&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-111827?style=flat-square&logo=amazonwebservices&logoColor=white)

### Software
![Go](https://img.shields.io/badge/Go-111827?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-111827?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-111827?style=flat-square&logo=javascript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-111827?style=flat-square&logo=postgresql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=white)

---

## Experience

<details>
<summary><strong>Dision Tech LLC</strong> · Full-Stack Engineer · Jul 2026 – Sep 2026</summary>

- Built Bash automation linking Gitea with an AI coding agent for issue triage, branch creation, and pull-request generation
- Added automated labeling, Git validation, build verification, and failure handling before merge
- Deployed the website, automation service, and preview environments on Ubuntu with Incus
- Provisioned isolated containers, networks, resource limits, and systemd-managed services
- Configured Nginx, health checks, scheduled snapshots, and preview synchronization
- Authored deployment and service-health test cases and documentation

</details>

<details>
<summary><strong>Chemizol</strong> · Software Engineer · Dec 2025 – Apr 2026</summary>

- Built a searchable React catalog covering 200+ chemical products
- Containerized the application with Docker
- Maintained a repeatable deployment workflow for stakeholder testing and review

</details>

<details>
<summary><strong>Aurion Technology</strong> · Software Engineer · Nov 2025 – Jan 2026</summary>

- Implemented Python application workflow states for donor-patient matching logic
- Integrated streaming AI responses into backend APIs
- Investigated and resolved pre-production stability issues

</details>

<details>
<summary><strong>RMIT University Vietnam × NextWay Technology</strong> · Backend Engineer (DevOps) · Mar 2025 – Sep 2025</summary>

- Supported deployment of a seven-service microservices application on GCP Cloud Run
- Automated build and deployment workflows with GitHub Actions and Google Cloud Build
- Containerized services with Docker to standardize local/cloud environments
- Integrated Firebase and Google Cloud Storage

</details>

---

## How I approach infrastructure

I optimize for a simple chain:

**Source → Validate → Build → Containerize → Deploy → Observe**

That means:

- version-controlled source and reproducible builds
- automated validation before deployment
- standardized runtime environments
- explicit service management on Linux
- health checks and operational visibility
- fewer manual steps and easier recovery when something fails

---

## Contact

I’m interested in work around **DevOps, cloud infrastructure, backend systems, automation, and deployment engineering**.

[LinkedIn](https://www.linkedin.com/in/le-xuanloc) · [GitHub](https://github.com/XU4NLOC) · [lexuanloc0501.work@gmail.com](mailto:lexuanloc0501.work@gmail.com)

<sub>Ho Chi Minh City, Vietnam</sub>
