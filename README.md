
# 🌩️ Cloud Native Application Development with IBM Cloud and Kubernetes

## 📘 Project Overview
This project demonstrates how to develop, containerize, and deploy a cloud-native application using **IBM Cloud**, **Kubernetes**, and **Docker**. The goal is to build a scalable and efficient application that can be easily managed and deployed in the cloud environment.

---

## 🚀 Tools & Technologies Used
- **IBM Cloud** – Cloud platform for deployment and management  
- **Docker** – Containerization tool to package the application  
- **Kubernetes** – For container orchestration and scaling  
- **Minikube** – To run Kubernetes locally  
- **kubectl** – Command-line tool to manage Kubernetes clusters  
- **IBM Cloud CLI** – To connect and interact with IBM Cloud  
- **IBM Cloud Container Registry** – To store Docker images securely  

---

## 🏗️ Project Phases
### **Phase 1:** Containerization
- Built the application using Docker  
- Created a `Dockerfile` and built a Docker image  
- Tested the container locally  

### **Phase 2:** Kubernetes Deployment
- Installed and configured **Minikube**  
- Created a `deployment.yaml` file for Kubernetes  
- Exposed the application using a Kubernetes service  

### **Phase 3:** IBM Cloud Integration
- Connected to **IBM Cloud** using the IBM Cloud CLI  
- Pushed the Docker image to **IBM Cloud Container Registry**  
- Deployed the application on the IBM Kubernetes Service  

### **Phase 4:** Testing and Monitoring
- Verified deployment using `kubectl get pods` and `minikube service` commands  
- Tested app accessibility through the exposed port  
- Ensured scalability and reliability in the cloud environment  

---

## 📂 Folder Structure




---

## 💡 Key Commands Used
```bash
# Build Docker image
docker build -t myapp .

# Run container locally
docker run -p 8080:8080 myapp

# Start Minikube
minikube start

# Deploy to Kubernetes
kubectl apply -f deployment.yaml

# Access the app
minikube service cloudnativeapp --url

