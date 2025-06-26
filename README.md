# 🚀 CI/CD Docker Web App with GitHub Actions

[![CI](https://github.com/ArijitDas2005/ci-cd-docker-webapp/actions/workflows/ci.yml/badge.svg)](https://github.com/ArijitDas2005/ci-cd-docker-webapp/actions)

This project demonstrates a fully automated **CI/CD pipeline** for a simple **Flask-based Python web app**, using **GitHub Actions** for integration and **Docker Hub** for container registry.

---

## 🛠️ Tech Stack

- **Python 3.12** / Flask
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
- Lint Python code (`flake8`)
- Run unit tests (`pytest`)
- Build Docker image
- Push image to Docker Hub

✅ `.dockerignore` for cleaner images  
✅ Unit test to validate app endpoint  
✅ Ready for deployment

---

## 🐳 Docker Image

The containerized app is also available on Docker Hub:

👉 [`arijit2005/ci-cd-docker-webapp`](https://hub.docker.com/r/arijit2005/ci-cd-docker-webapp)

To pull and run the app locally:

```bash
docker pull arijit2005/ci-cd-docker-webapp
docker run -p 5000:5000 arijit2005/ci-cd-docker-webapp
