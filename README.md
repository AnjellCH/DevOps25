# DevOps25 🚀

Welcome to the **DevOps25** project! This repository is part of my Cloud Resume Challenge (AWS) and demonstrates foundational DevOps skills, including:

- Hosting a static resume website
- Writing infrastructure-as-code
- Automating builds with CI/CD

---

## 🧠 Project Overview

This project hosts my professional resume as a static HTML page and includes the following:

- `index.html`: My HTML resume
- `style.css`: Styling for the resume (if added)
- `buildspec.yml`: AWS CodeBuild configuration for CI/CD
- `my_app.py`: Placeholder or backend script (future use or demo)
- `textfile.txt`: Initial test or sample file

---

## 🛠️ Tools & Technologies Used

- **HTML/CSS** – for the static site
- **AWS S3** – static website hosting
- **AWS CodeBuild** – continuous deployment from GitHub
- **GitHub Actions** (optional) – for CI automation
- **Git/GitHub** – version control and collaboration

---

## 📦 Deployment

The site is automatically deployed to an S3 bucket using AWS CodeBuild. Here's how deployment is handled:

1. On push to `main`, CodeBuild is triggered.
2. `buildspec.yml` defines the build steps.
3. Artifacts are pushed to S3 for public hosting.

---

## 📁 Folder Structure


