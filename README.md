# Kubernetes Application Deployment

This repository contains Kubernetes configuration files for deploying a suite of applications, including MySQL, Memcached, RabbitMQ, and a main application service.

## Overview

- **Secrets**: Manages sensitive data such as database passwords and RabbitMQ credentials.
- **MySQL**: Deployment and service for the MySQL database, configured with persistent storage.
- **Memcached**: Deployment and service for caching data to improve application performance.
- **RabbitMQ**: Deployment and service for message queuing, facilitating communication between services.
- **Main Application**: Deployment and service for the primary application, connecting to the database and cache.

## Components

1. **Secrets**: 
   - Stores sensitive information securely.
   
2. **MySQL**: 
   - Deployment for database management.
   - Service for internal communication.

3. **Memcached**: 
   - Deployment for in-memory caching.
   - Service for internal communication.

4. **RabbitMQ**: 
   - Deployment for message queuing.
   - Service for internal communication.

5. **Main Application**: 
   - Deployment for the core application logic.
   - LoadBalancer service for external access.

## Notion Page
Check outputs and code explanations at the Notion page: [Vprofile App Deployment on Kubernetes Cluster](https://abdulsuboor.notion.site/App-Deployment-on-Kubernetes-Cluster-109bdf64ccc680af8c6dd4986f41b4f4?pvs=4)
