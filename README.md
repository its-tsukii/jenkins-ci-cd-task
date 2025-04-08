# 🚀 Jenkins CI/CD Pipeline – Internship Task 1

This project showcases a basic CI/CD pipeline setup using Jenkins and GitHub to build and deploy a simple HTML application. It is part of the **Uptoskills Cloud Internship** program.

---

## 📌 Task Objective

> Create a Jenkins pipeline that builds and deploys an application automatically when code is pushed to GitHub.

---

## 📁 Project Structure

jenkins-pipeline-task/ 
│ ├── Jenkinsfile 
│ ├── index.html 
├── app/ 
├── index.html 
├── Dockerfile 
├── Readme.md
├── LICENSE
└── screenshots/ 
│ ├── app-running.png 
│ ├── jenkins-config.png 
│ ├── pipeline-success.png 
│ ├── console-output.png



---

## 🖥️ App Running on Localhost

> This is the final deployed app running on `http://localhost:8081`.

![App Running](screenshots/app-running.png)

---

## 🔧 Jenkins Job Configuration

> GitHub integration and Script Path settings.

![Jenkins Config](screenshots/jenkins-config.png)

---

## ⚙️ Jenkinsfile Pipeline

A simple declarative Jenkins pipeline:
```
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'echo Building the app...'
            }
        }

        stage('Deploy') {
            steps {
                bat 'start index.html'
            }
        }
    }
}
```
✅ Pipeline Success
A successful pipeline run from the Jenkins dashboard:


Console Output:


📚 How to Run Locally
bash
Copy
Edit
git clone https://github.com/yourusername/jenkins-ci-cd-task
cd jenkins-pipeline-task
start index.html
Make sure port 8081 is available if you're using a local server.

🔨 Tools & Tech Used
Jenkins

GitHub

HTML

Git (CLI)

Windows OS

🌐 Author
Aayush Kukade
GitHub • Medium
