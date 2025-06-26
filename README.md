# 🚀 CI/CD Docker Web App with GitHub Actions

This project demonstrates a fully automated **CI/CD pipeline** for a simple **Flask-based Python web app**, using **GitHub Actions** for integration and **Docker Hub** for container registry.

---

## 🛠️ Tech Stack

- **Python 3.9** / Flask
- **Docker** (Containerization)
- **GitHub Actions** (CI/CD)
- **Docker Hub** (Image Registry)
- **Pytest** (Unit Testing)
- **Flake8** (Linting)

---

## 📦 Features

✅ Simple Python Flask Web App  
✅ Dockerfile for containerization  
✅ GitHub Actions Workflow to:
- Lint Python code (flake8)
- Run unit tests (pytest)
- Build Docker image
- Push image to Docker Hub

✅ `.dockerignore` for cleaner image  
✅ Unit test to validate app endpoint  
✅ Ready for deployment

---

## 🚀 Local Setup

Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/ci-cd-docker-webapp.git
cd ci-cd-docker-webapp
pip install -r requirements.txt
python app.py
