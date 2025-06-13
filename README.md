# 🚀 Java Full Stack DevOps Project

This is a Java-based full-stack application demonstrating CI/CD automation using Git, Maven, Docker, and Jenkins. It consists of a frontend running on port `3000` and a backend API hosted on port `9090`. CI/CD is managed using a Jenkins pipeline configured in the Jenkins server (not via Jenkinsfile).

---

## 🔧 Tech Stack

- **Frontend**: React (or similar, running on `http://localhost:3000`)
- **Backend**: Java (JDK 17), Spring Boot  
- **Build Tool**: Maven  
- **CI/CD**: Jenkins (configured in UI)  
- **Containerization**: Docker  
- **Orchestration**: Docker Compose  
- **Version Control**: Git + GitHub  

---

## 🌐 Application URLs

| Layer      | URL                                | Description               |
|------------|-------------------------------------|---------------------------|
| Frontend   | `http://localhost:3000`            | User Interface            |
| Backend    | `http://localhost:9090/api/employees` | REST API Endpoint         |
| Jenkins UI | `http://localhost:8080`            | CI/CD Dashboard (Jenkins) |

---



## 🐳 Run Entire Stack with Docker Compose

```bash
# Clone the repo
git clone https://github.com/im-faix/java-app-DevOps.git
cd java-app-DevOps

# Start all services (frontend, backend, Jenkins)
docker-compose up -d --build
✅ Features
Multi-container full stack setup

Backend REST APIs tested with Postman or browser

Jenkins pipeline automates build & deploy on Git push

Frontend connects to backend via API call to /api/employees

🧪 Testing the App
After containers are up:

Visit frontend: http://localhost:3000

Access REST API: http://localhost:9090/api/employees

Jenkins UI: http://localhost:8080

🙋‍♂️ Author
Mohammed Faizan

GitHub: @im-faix
