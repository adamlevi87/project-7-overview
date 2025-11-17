# Project-7: a Devops story

## 🚀 Project Origin Story

This project originated from a real-world scenario that every DevOps team encounters: **a developer created an application that "works on my machine"** and we were tasked with everything needed to move it from a local development to a production-ready cloud environment.

What started as a simple app running locally evolved into a comprehensive demonstration of enterprise-grade DevOps practices, showcasing how to transform a basic application into a scalable, secure, and maintainable cloud-native deployment.

## 🏗️ Implementation Repositories

This project is organized across three specialized repositories that work together to create a complete end-to-end deployment pipeline:

**[🏗️ project-7-tf](https://github.com/adamlevi87/project-7-tf)** - Infrastructure as Code  
Terraform configurations for AWS infrastructure, EKS cluster, ArgoCD deployment, and self-hosted GitHub runners.

**[🚀 project-7-app](https://github.com/adamlevi87/project-7-app)** - Application and CI/CD  
Node.js Express application with unified CI/CD pipeline, comprehensive testing, container signing, and GitOps integration.

**[📋 project-7-gitops](https://github.com/adamlevi87/project-7-gitops)** - Deployment Management  
Kubernetes manifests, environment-specific configurations, and automated deployment workflows managed by ArgoCD.
