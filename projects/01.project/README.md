# 🚀 CI/CD Pipeline with Azure AKS, Terraform, Prometheus & Grafana

## 📌 Project Overview

This project implements a **CI/CD pipeline** to deploy applications on **Azure Kubernetes Service (AKS)** using **Terraform**, while monitoring the cluster and applications with **Prometheus** and **Grafana**.

![Project architecture](assets/main_gif.gif)

## 🎯 Key Components

1. **Version Control (GitHub/GitLab)** 📂
    
    - Stores application source code and Terraform configurations.
        
    - Triggers CI/CD workflows upon changes.
        
2. **CI/CD Pipeline (GitHub Actions/Jenkins)** 🔄
    
    - Automates build, test, and deployment processes.
        
    - Pushes container images to a container registry (Azure Container Registry).
        
    - Deploys applications to AKS using Helm/Kubernetes manifests.
        
3. **Infrastructure as Code (Terraform)** 🏗️
    
    - Provisions and manages Azure Kubernetes Service (AKS).
        
    - Creates networking, storage, and required resources in Azure.
        
4. **Azure Kubernetes Service (AKS)** ☁️
    
    - Hosts and runs containerized applications.
        
    - Manages deployments, scaling, and networking.
        
5. **Monitoring with Prometheus & Grafana** 📊
    
    - **Prometheus**: Collects and stores metrics from Kubernetes nodes, pods, and applications.
        
    - **Grafana**: Provides visual dashboards for real-time monitoring.
        

## 🔧 Setup & Deployment

### Prerequisites

- Azure subscription ⚡
    
- Terraform installed 🏗️
    
- Kubernetes CLI (kubectl) installed 🖥️
    
- Helm installed 🎡
    
- GitHub Actions/Jenkins configured for CI/CD ⚙️

## [Source code](https://github.com/suriya1776/microservices-demo/tree/main)

### 📌 Step-by-Step Workflow

🔹 **Step 1** - [🚀 CI/CD with GitHub Actions](01.md)

- Automate builds, tests, and deployments using **GitHub Actions**.
    

🔹 **Step 2** - [🛡️ Static Code Scanning using SonarQube](02.md)

- Analyze code quality and detect vulnerabilities with **SonarQube**.
    

🔹 **Step 3** - [🔍 Image Scanning using Trivy](03.md)

- Ensure container security by scanning Docker images for vulnerabilities using **Trivy**.
    

🔹 **Step 4** - [🚢 Deployment in AKS Cluster](04.md)

- Deploy the application securely into **Azure Kubernetes Service (AKS)**.
    

🔹 **Step 5** - [📊 Monitoring with Prometheus & Grafana](05.md)

- Set up **Prometheus** for metrics collection and **Grafana** for visualization.


✅ Benefits

Automated Deployments: Faster and more reliable deployments.

Scalability: Easily scales applications using AKS.

Real-time Monitoring: Get insights into cluster and application health.

Infrastructure as Code: Reproducible and maintainable infrastructure setup.

📌 Conclusion

This project integrates CI/CD with Terraform, Kubernetes, and Monitoring to streamline application deployment and management in Azure. 🚀🔥