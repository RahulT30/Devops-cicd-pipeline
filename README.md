# Devops-cicd-pipeline
A sample project which uses cicd docker and kubernetes to deploy a simple flask app.

This project demonstrates a CI/CD pipeline:
- Python Flask app
- Dockerized and stored in DockerHub
- Jenkins pipeline automates build & deployment
- Kubernetes (Minikube) hosts the running application

## Steps
1. Code → GitHub
2. Jenkins → builds & pushes Docker image
3. Deploys to Kubernetes cluster
