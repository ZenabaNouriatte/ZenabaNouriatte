# 👩🏾‍💻 Zenaba Nouriatte

Welcome to my GitHub! 

## About Me

 **Zenaba Nouriatte**  
 **34 years old**  
 **42 School Student** since **November 2023**  
 **Career Goal:** Cloud Engineer & DevOps Specialist  
 **Next Step:** Actively seeking a DevOps internship starting January 2026

### 🔄 Career Transition Journey
From **10 years in social work** to **DevOps and cloud engineering** – bringing project management expertise and problem-solving mindset to infrastructure challenges.

💡 Currently developing a strong interest in **AWS Cloud technologies** and preparing for the **AWS Certified Cloud Practitioner** and **AWS Certified AI Practitioner** certifications.

---

## Current Tech Focus

This GitHub showcases my journey toward **cloud engineering** and **DevOps** through:

### System Administration
- Linux system management & automation  
- Bash scripting for infrastructure tasks  
- Network configuration & troubleshooting  

### Cloud & DevOps Learning Path
- Container technologies (Docker)  
- Infrastructure as Code principles  
- CI/CD pipeline concepts  
- Cloud architecture patterns (AWS focus)  

### 42 School Projects
- Low-level C programming  
- Unix system programming  
- Network programming & protocols  

---

##  Learning Roadmap

| Focus Area             | Current Status                  | Next Steps                          |
|------------------------|----------------------------------|--------------------------------------|
| **42 Core Curriculum** | 🟩🟩🟩🟩🟩 *Completed — Tronc Commun validated*  |  Completing RNCP 7            |
| **Linux & System Admin** | 🟩🟩🟩⬜⬜ Solid foundations       | Advanced automation scripts          |
| **Cloud Fundamentals** | 🟩🟩⬜⬜⬜ Learning AWS basics     | AWS Cloud Practitioner cert          |
| **DevOps Tools**       | 🟩🟩⬜⬜⬜ Docker basics / Terraform / Monitoring & Observability   | CI/CD pipelines, IaC                 |

---

## 🌱 Currently Learning

- **AWS Cloud Services** – EC2, VPC, S3, IAM  
- **Docker & Containerization** – Building and orchestrating containers  
- **Infrastructure Automation** – Terraform, Ansible and Kubernetes basics  
- **CI/CD Concepts** – Jenkins, GitLab CI, GitHub Actions  
- **Monitoring & Observability** – System metrics and logging  

---


### ☁️ Deploying my portfolio on AWS (S3 + Lambda + DynamoDB)

#### Completed (via AWS Console)
- Static website hosting on **S3** with a custom domain  
- Domain configuration through **OVH**  
- SSL certificate issued with **AWS Certificate Manager**  
- **Visitor counter** implemented with **AWS Lambda**  
- Visit data stored in **DynamoDB**  
- HTTPS enforced with **CloudFront**, DNS routing configured via OVH  

#### To improve / next steps
- **CI/CD with GitHub Actions** for automated frontend and Lambda deployments  
- **Secrets management** using GitHub Actions and IAM roles  
- **Functional tests** (Lambda + DynamoDB) to be expanded  

**My Goal:** Build a serverless architecture to host my portfolio and gain hands-on experience with AWS core services and IaC (S3, Lambda, DynamoDB, CloudFront, ACM, CI/CD).  
**Result:** [www.zenabamogne.fr](https://www.zenabamogne.fr/)


---

### ⭐ Main Project — ft_transcendence  
**Fullstack Deployment • Docker • NGINX • SSL • CI via GitHub Actions • Monitoring (Prometheus / Grafana / ELK)**

As part of the final stage of the 42 curriculum, I deployed a real-time multiplayer web application with a **production-style infrastructure**.  
This project was my main playground to practise **DevOps, networking, security and observability**.

#### 🔧 Infrastructure & Deployment

- **Dockerized architecture**:
  - Separate containers for **frontend** and **backend**
  - **SQLite** database handled directly by the backend (no separate DB container)
- **NGINX reverse proxy** in front of the stack:
  - Reverse routing to frontend & backend
  - HTTP → HTTPS redirection
  - Static asset delivery
- **TLS / SSL**:
  - HTTPS enforced for all external access
  - Certificates configured at the reverse proxy level

#### 🔐 Security & Networking

- Isolated Docker network for application services  
- Basic hardening of NGINX configuration (security headers, routing rules)  
- Controlled exposure of ports (only proxy exposed publicly)

#### 🔄 CI with GitHub Actions

- **GitHub Actions pipeline** triggered on pushes/PRs:
  - Build & test steps for the backend
  - Custom test script to validate core features before manual deployment
- Build feedback integrated into the development workflow (pass/fail status on commits)

#### 📈 Monitoring & Observability

- **Prometheus** used to scrape metrics from the application and/or infrastructure  
- **Grafana** dashboards to visualize performance and health indicators  
- **ELK stack (Elasticsearch / Logstash / Kibana)** to centralize and explore logs:
  - Application logs
  - Reverse proxy / access logs

####  Technical Outcomes

- Ran a **fullstack app** behind a reverse proxy with HTTPS  
- Practised **containerization, networking and security** on a non-trivial project  
- Set up **CI** to systematically test changes before deployment  
- Implemented **monitoring and log collection** with Prometheus/Grafana and ELK, getting closer to real-world DevOps workflows


---

## Planned Projects

### Microservices Architecture with Kubernetes
Deploying a microservice-based application on a Kubernetes cluster:  
- Service management, ingress controller, persistent storage  
- Monitoring with Prometheus/Grafana and automated deployment  
   Goal: Understand container orchestration and scalable architecture.

---

### CI/CD Pipeline with DevSecOps
Creating a secure, automated CI/CD workflow:  
- Static code analysis, vulnerability scanning, automated tests  
- GitHub Actions or GitLab CI/CD for deployment  
   Goal: Automate software lifecycle with a security-first approach.

---

## 💼 Professional Background

**Unique Value Proposition:**  
Combining technical skills with 10 years of project management experience in high-stakes environments.

**Transferable Skills:**
- Complex project coordination  
- Stakeholder management  
- Problem-solving under pressure  
- Cross-functional collaboration  

---

## 🔗 Connect With Me

📧 **Email:** *zenaba.mogne@live.fr*  
💼 **LinkedIn:** [linkedin.com/in/zenaba-mogne](https://linkedin.com/in/zenaba-mogne)  
🌐 **Portfolio:** [www.zenabamogne.fr](https://www.zenabamogne.fr/)

---

💡 **Open to:** DevOps internships, mentorship opportunities, and connecting with fellow career changers in tech!

> *"From social impact to cloud infrastructure – ready to apply human-centered problem-solving to technical challenges."*
