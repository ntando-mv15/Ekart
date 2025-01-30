# Java Shopping Cart - Dockerized & Automated Deployment 

This project entails a Java-based shopping cart web application that is **Dockerized** and **automatically deployed** using GitHub Actions. The final application runs inside a Docker container on an **EC2 instance**.

---

## 📌 Project Overview

This project automates the **containerization** and **deployment** of a Java web application using modern DevOps practices.

### ✅ Key Features:
- **Dockerized Java Application** - The app runs inside a container.
- **GitHub Actions for CI/CD** - Automates the build and deployment process.
- **Deployment to EC2** - The app is hosted on an AWS EC2 instance.
- **Fully Automated Workflow** - Push your code, and GitHub Actions does the rest.

---

### CI/CD Workflow (GitHub Actions)

Each time you push new code to the repository, GitHub Actions:
1. **Builds the Docker Image** 
2. **Pushes it to Docker Hub (or AWS ECR)** 
3. **Deploys the Container to an EC2 instance** 🚀

## Project Documentation

Find detailed project implementation here:

[Medium Article](https://medium.com/@ntando.mv15/project-dockerizing-a-java-application-with-github-actions-4a9537077875)

---

## Future Enhancements
- Add Kubernetes support (K8s).
- Implement a monitoring solution (Prometheus + Grafana).
- Use Terraform to provision infrastructure.








