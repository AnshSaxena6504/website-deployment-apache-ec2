# 🌐 Website Deployment on Apache (AWS EC2) - DevOps Project

This repository contains a structured static website project designed for deployment on an **Apache web server** hosted on an **AWS EC2 instance**. The project is organized following DevOps best practices including version control, infrastructure configuration, deployment scripting, and clear separation of concerns.

---

## 📦 Project Overview

- **Type**: Static website (HTML, CSS, JS)
- **Hosted On**: AWS EC2 (Ubuntu)
- **Web Server**: Apache2
- **Deployment Method**: Manual (via Bash script), ready for CI/CD integration
- **Use Case**: DevOps practice, portfolio project, or template for real-world deployment

---

## 🚀 Deployment Guide

### ✅ Pre-requisites

Before deploying, make sure the following are set up:

- ✅ Apache2 installed on the EC2 instance:
  ```bash
  sudo apt update
  sudo apt install apache2
