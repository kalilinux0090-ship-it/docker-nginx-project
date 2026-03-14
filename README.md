# Docker Nginx Project

## Project Objective
- Deploy a simple Nginx web server using Docker & Docker Compose
- Serve a static HTML page
- Automated deployment using Ansible (optional next step)
- Version controlled with Git & GitHub

## Folder Structure
docker-nginx-project/
├── app/
│   └── index.html
├── Dockerfile
├── docker-compose.yml
└── README.md

## How to Run
### Locally
docker-compose build
docker-compose up -d

Open browser: http://localhost:8080

### Using Ansible (Future)
ansible-playbook docker/playbook-docker.yml --ask-become-pass

## Features
- Docker containerization
- Docker Compose orchestration
- GitHub version control
- Optional: Automated deployment via ansible
