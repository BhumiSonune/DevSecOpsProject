# 🚀 Secure DevSecOps CI/CD Pipeline with Kubernetes

## 📌 Overview
Designed and implemented a complete **DevSecOps CI/CD pipeline** to automate build, security testing, containerization, deployment, and monitoring of a full-stack web application.  
Security checks are integrated at every stage to ensure fast, reliable, and secure releases.

---

## 🏗 Architecture
```
GitHub → Jenkins → SonarQube → Docker → Trivy → Kubernetes → OWASP ZAP → Prometheus/Grafana
```

---

## 🛠 Tech Stack
- **CI/CD:** Jenkins, GitHub  
- **Security:** SonarQube (SAST), Trivy (Container Scan), OWASP ZAP (DAST)  
- **Containers:** Docker, Docker Compose  
- **Orchestration:** Kubernetes (kubeadm)  
- **Monitoring:** Prometheus, Grafana  
- **Backend:** Node.js + Express  
- **Frontend:** HTML, CSS, JavaScript  
- **OS:** Debian Linux (VMware)

---

## ⚙️ Infrastructure
- VM1 – Jenkins + SonarQube  
- VM2 – Kubernetes Master  
- VM3 – Kubernetes Worker  

---

## 🔄 CI/CD Pipeline Stages
1. Source code checkout from GitHub  
2. Static code analysis using SonarQube  
3. Docker image build  
4. Trivy vulnerability scanning  
5. Deployment to Kubernetes  
6. Dynamic security testing using OWASP ZAP  
7. Monitoring with Prometheus & Grafana  

---

## 🚀 Run Locally
```bash
docker-compose up --build
```
Access: http://localhost

---

## 👩‍💻 My Responsibilities
- Designed Jenkins CI/CD pipeline  
- Integrated security tools (SonarQube, Trivy, OWASP ZAP)  
- Dockerized frontend and backend services  
- Deployed application on Kubernetes cluster  
- Configured monitoring dashboards  
- Automated secure end-to-end deployments  

---

## 🎯 Outcome
- Faster automated releases  
- Early vulnerability detection  
- Secure containerized deployment  
- Production-ready DevSecOps workflow  

---

**Author:** Bhuvaneshwari Sonune  
DevSecOps | Cloud | Security
