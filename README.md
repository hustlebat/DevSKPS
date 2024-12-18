# DevSKPS
# DevSecOps Lab Scenario

In this lab, you will set up a DevSecOps environment spanning two logical servers:
- **dsb-node-01**: Runs NGINX (as a reverse proxy), Docker (for containerization), a containerized web application, Prometheus (for metrics collection), and Grafana (for metrics visualization).
- **dsb-hub**: Runs NGINX, Gitea (Git service), SonarQube (code quality), Jenkins (CI/CD), Trivy (vulnerability scanner), Nexus (artifact repository), and Docker.

By the end of this lab, you will:
1. Understand how to run these services in Docker containers.
2. Learn how to integrate Prometheus and Grafana for monitoring.
3. Explore a CI/CD pipeline using Jenkins, SonarQube, and Nexus.
4. Manage code repositories in Gitea and ensure their security with Trivy.


