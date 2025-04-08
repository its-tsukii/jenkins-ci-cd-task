# Jenkins CI/CD Task 1 – Internship Project 🚀

This repository contains my submission for Task 1 of the Uptoskills Cloud Computing Internship. It demonstrates a working Jenkins pipeline setup that builds and deploys a simple web application.

## ✅ Task Summary

- Installed Jenkins locally.
- Created a Jenkinsfile to automate build and deploy.
- Configured Jenkins to pull from this GitHub repository.
- Triggered the pipeline using `git push`.
- Served a basic HTML page on `http://localhost:8081`.

## 🏗️ Tech Stack

- Jenkins
- GitHub
- HTML
- Windows (localhost)

## 📂 Folder Structure

jenkins-pipeline-task/
<br>├── app/
<br>    └── index.html
<br>├── Dockerfile 
<br>├── LICENSE
<br>├── Jenkinsfile 
<br>├── Readme.md
<br>└── index.html

## 🔧 How it works

- Jenkins pulls code from GitHub.
- Builds the project (static HTML in this case).
- Deploys it by copying to a folder and serving via Python HTTP server on port 8081.

## 📸 Screenshots

<!-- Add your screenshots here -->

## 📖 Blog

Check out the full story on [Medium](#) (link coming soon).

---

### 📄 License

This project is licensed under MIT.
