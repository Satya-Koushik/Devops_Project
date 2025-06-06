# DevOps_Project

## DevOps Lifecycle Implementation for a Dockerized Web Application

### Problem Statement
Abode Software, a product-based company, aims to implement a complete DevOps lifecycle for their web application hosted on GitHub. The solution must automate server provisioning, establish Git-based workflows, containerize the application, and configure CI/CD pipelines that trigger based on branch activity. All components should support consistent, efficient, and repeatable deployments using Jenkins and Docker.

### Project Description
This project implements a full DevOps lifecycle for a web application using open-source tools. Server setup is automated using Ansible, while Jenkins handles CI/CD pipelines triggered by Git branch events. The application is containerized using Docker, and builds are triggered automatically on every code push. The workflow includes distinct behaviors for `master` and `develop` branches, and all services run on Linux-based systems to ensure environment consistency.

### Tools & Technologies Used
- **Ansible** – for configuration management and server provisioning  
- **Jenkins** – for building CI/CD pipelines  
- **Docker** – to containerize the application  
- **Git & GitHub** – for version control and source code management  
- **Linux** – as the deployment environment  

### Key Responsibilities
- Automated server provisioning and software setup using **Ansible**
- Designed and managed **Jenkins pipelines** with stages: `build`, `test`, and `prod`
- Implemented **branch-specific CI/CD**:
  - Commits to `develop` trigger build and test stages
  - Commits to `master` trigger full deployment to production
- Containerized the web application using a custom **Dockerfile**, based on the `hshar/webapp` image
- Maintained all components and workflows within **Linux** environments
