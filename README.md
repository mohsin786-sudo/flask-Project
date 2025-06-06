# CI/CD Pipeline for Dockerized Python Flask Web App

This project sets up a **CI/CD pipeline** using **GitHub Actions** to build, test, and deploy a Dockerized Python Flask web application automatically to a virtual Ubuntu server.

---

## Tech Stack

- Python 3.9 + Flask
- Docker (containerization)
- GitHub Actions (CI/CD)
- Ubuntu virtual server (deployment target)
- Git & GitHub (version control)

---

## Project Structure

- `Dockerfile` — Defines how to containerize the Flask app
- `.github/workflows/ci-cd.yml` — GitHub Actions workflow to automate build and deployment
- `app.py` — Main Flask application
- `requirements.txt` — Python dependencies

---

## Prerequisites

- Docker installed locally and on the remote Ubuntu server
- SSH access to your remote Ubuntu server
- Git installed and configured locally
- GitHub repository created and linked to the project

---

## Local Setup and Run

1. **Clone the repository**

   ```bash
   git clone https://github.com/mohsin786-sudo/flask-Project.git
   cd flask-Project
