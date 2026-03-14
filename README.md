# Springer Capital CI/CD Pipeline

## What This Project Does
Automated CI/CD pipeline that builds and deploys
Docker containers on every code push.

## Tools Used
- GitHub Actions — automation
- Docker — containerization  
- Bash — scripting
- Prometheus + Grafana — monitoring

## How CI/CD Works
1. Push code to master branch
2. GitHub Actions triggers automatically
3. Builds Docker image
4. Pushes to Docker Hub
5. Deploys to server

## How to Run Locally
chmod +x app.sh
./app.sh
```
