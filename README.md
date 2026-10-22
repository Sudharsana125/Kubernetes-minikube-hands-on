\# ☸️ Kubernetes Hands-On



I built a simple web application using Docker, Minikube, and Kubernetes to learn how to deploy and run applications in containers. Through this small hands-on , I learned how to manage multiple replicas and make the application accessible using a Kubernetes Service.



\### Tech Stack

Docker • Kubernetes • Minikube • Nginx • HTML • CSS



\###  Run Locally

```bash

minikube start --driver=docker

kubectl apply -f deployment.yaml

minikube service nginx-service

```



