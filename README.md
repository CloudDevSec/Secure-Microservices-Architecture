# Secure Microservices Architecture

## Project Overview
This project demonstrates a secure microservices architecture using Spring Boot and Node.js. The architecture includes secure communication, an API gateway, a service mesh, centralized logging, and secrets management.

## Features
- **Microservices Development:** Spring Boot for Java services and Node.js for JavaScript services.
- **Secure Communication:** Mutual TLS (mTLS) between services.
- **API Gateway:** Traefik for routing with rate limiting, IP whitelisting, and JWT validation.
- **Service Mesh:** Istio for enhanced security features like automatic mTLS and traffic encryption.
- **Centralized Logging and Monitoring:** ELK/EFK stack with security alerts.
- **Secrets Management:** Vault by HashiCorp.

## Setup Instructions

### Prerequisites
- Docker and Kubernetes setup.
- Istio installation.
- Vault installation.
- ELK/EFK stack setup.
