# Kubernetes Learning Project

This is my first Kubernetes configuration project where I'm learning how to containerize and orchestrate applications using Kubernetes.

## About This Project

I'm learning Kubernetes fundamentals through hands-on practice with Docker and Kubernetes. This project contains basic Kubernetes manifests for deploying a Node.js application.

## Learning Journey

- **Goal**: Understand Kubernetes core concepts and configuration
- **Level**: Beginner - First time configuring Kubernetes
- **Focus Areas**:
  - Deployments
  - Services
  - Resource management
  - Container orchestration

## Learning Resources

- **Course**: [Docker & Kubernetes: The Complete Guide](https://www.udemy.com/course/docker-kubernetes-the-practical-guide/)
- **Instructor**: Maximilian Schwarzmüller
- **Platform**: Udemy

## Project Structure

- `deployment.yml` - Kubernetes Deployment configuration for the application
- `service.yml` - Kubernetes Service configuration for exposing the application

## Key Concepts I'm Learning

- **Deployments**: Managing containerized applications
- **Services**: Exposing applications within and outside the cluster
- **Resource Management**: Setting CPU and memory requests/limits
- **Labels & Selectors**: Organizing and managing Kubernetes objects

## Getting Started

To deploy this application to your Kubernetes cluster:

```bash
kubectl apply -f deployment.yml
kubectl apply -f service.yml
```

To check the deployment status:

```bash
kubectl get deployments
kubectl get services
kubectl get pods
```

## Notes

This is a learning project. As I progress through the course, I'll be adding more advanced configurations and best practices.

