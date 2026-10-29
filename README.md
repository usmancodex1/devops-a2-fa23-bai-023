# DevOps Assignment 2 - Personal Portfolio

**Name:** Muhammad Usman  
**Roll No:** fa23-bai-023  
**Course:** DevOps for Cloud Computing Lab

A static HTML/CSS portfolio served by Nginx in Docker, with CI on GitHub Actions.

## Run locally with Docker
```
docker build -t usman11111/devops-a2:manual .
docker run -d -p 8080:80 --name portfolio usman11111/devops-a2:manual
```
Open http://localhost:8080
