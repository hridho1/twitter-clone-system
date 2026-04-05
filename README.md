# Twitter Clone – Microservices System

This project is a fully containerized microservices-based social media platform.

## Architecture
- API Gateway (Spring Boot)
- User Service (PostgreSQL)
- Tweet Service (MongoDB)
- Chat Service (PostgreSQL)
- Service Discovery (Eureka)

## Features
- Authentication via Auth0
- CI/CD pipeline (GitLab)
- Kubernetes deployment (GCP)
- Load testing (K6)
- Monitoring (Grafana + Prometheus)

## Demo
- System Demo (From Production): https://youtu.be/5u4aYHSSD2c
- Right to be forgotten: https://youtu.be/ZLrX4hS-F1o
- E2E Testing: https://youtu.be/aetEz9YsT28
- Load testing with Kubernetes: https://youtu.be/g5Ic8qVXygY
- Monitoring + App Demo: https://youtu.be/pG49l54UEiE
- Monitoring + Load Test: https://youtu.be/4KAOOuPOnuI

## Key Highlights
- Autoscaling with Kubernetes HPA
- Event-driven communication (RabbitMQ)
- Achieved >80% test coverage with SonarQube

## Repositories
- **API Gateway:** https://github.com/hridho1/twitter-clone-api-gateway
- **Discovery service:** https://github.com/hridho1/twitter-clone-discovery-service
- **User Service** → https://github.com/hridho1/twitter-clone-user-service
- **Tweet Service** → https://github.com/hridho1/twitter-clone-twitter-service
- **Chat Service** → https://github.com/hridho1/twitter-clone-chat-service
- **Frontend** → https://github.com/hridho1/twitter-clone-frontend
