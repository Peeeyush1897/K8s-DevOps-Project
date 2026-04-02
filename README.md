# 🚀 Kubernetes Deployment Project

## 📌 Overview

This project demonstrates deployment of an application using Kubernetes (Minikube).

## 🛠️ Tools Used

* Kubernetes
* Minikube
* Docker
* kubectl

## 📂 Files

* deployment.yaml → Defines pods and containers
* service.yaml → Exposes application

## 🚀 Steps to Run

### 1. Start Minikube

minikube start

### 2. Apply Deployment

kubectl apply -f deployment.yaml

### 3. Apply Service

kubectl apply -f service.yaml

### 4. Check Pods

kubectl get pods

### 5. Access Application

minikube service <service-name>

## 🎯 Outcome

Successfully deployed application on Kubernetes cluster using Minikube.

## 👨‍💻 Author

Peeyush Kumar Nahar
