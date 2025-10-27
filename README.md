# 🚀 DevOps Scripting Labs — Python 🐍 + Go 🐹

A 7-day hands-on practice plan to master scripting as a **DevOps Engineer**.

This repository contains daily exercises written in both **Python** and **Go**, focusing on:
- System automation
- CI/CD integration
- Docker & Kubernetes management
- Cloud operations (Azure / AWS)
- Real-world DevOps use cases

---

## 🗓️ Daily Structure

| Day | Focus | Python Script | Go Script |
|-----|--------|----------------|------------|
| 1 | Fundamentals | `system_info.py` | `sysinfo.go` |
| 2 | File Automation | `log_backup.py` | `filewalker.go` |
| 3 | System Health | `monitor.py` | `healthcheck.go` |
| 4 | Docker Automation | `docker_cleanup.py` | `dockercli.go` |
| 5 | CI/CD API | `azure_pipeline_report.py` | `pipelinecli.go` |
| 6 | Cloud / K8s | `k8s_s3_uploader.py` | `k8sstatus.go` |
| 7 | Final Project | `devops_dashboard_api.py` | `dashboard_client.go` |

---

## 🧩 Daily Goals

- 🐍 **Python** — focus on automation, REST APIs, monitoring
- 🐹 **Go** — focus on concurrency, CLI tools, REST clients

Each day includes:
- 1 Python script
- 1 Go script
- A short README explaining the logic

---

## 🧠 Final Project: DevOps Scripting Dashboard

Combine your Python & Go knowledge into a real-world automation tool:

- Backend: **Python FastAPI** — exposes system, Docker, and CI/CD metrics  
- CLI Client: **Go** — fetches and displays data in the terminal  
- Optional Frontend: React / HTML dashboard  

**Goal:** Automate monitoring & DevOps insights in a single project.

---

## ⚙️ Setup Instructions

```bash
# Clone repo
git clone https://github.com/<your-username>/devops-scripting-labs.git
cd devops-scripting-labs

# Python setup
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt

# Go setup
go mod init devops-scripting-labs
go get
