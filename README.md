# DevOps Capstone Project

## Technologies Used
- GitHub
- Jenkins
- Docker
- AWS EC2
- Prometheus
- Grafana
- Bash
- Cron

## Setup Instructions

### Run Locally

npm install
npm start

### Build Docker Image

docker build -t devops-capstone .

### Run Container

docker run -d -p 3000:3000 devops-capstone

## CI/CD Pipeline Flow

GitHub → Jenkins → Docker Hub → AWS EC2 → Monitoring
