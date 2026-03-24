# DevOps CI/CD Pipeline Project

This project demonstrates a complete CI/CD pipeline using GitHub Actions, Docker, Docker Hub, and AWS EC2.

## Technologies Used
- Docker
- GitHub Actions
- AWS EC2 (Ubuntu)
- Nginx
- Linux
- SSH

## CI/CD Pipeline Flow
1. Developer pushes code to GitHub
2. GitHub Actions pipeline is triggered
3. Docker image is built
4. Image is pushed to Docker Hub
5. GitHub Actions connects to AWS EC2 via SSH
6. EC2 pulls latest Docker image
7. Docker container is restarted
8. Website is updated automatically

## Live Application
http://3.79.44.134

## Author
Hamza Terzi
