# Deploying Java Web Application using Docker and Kubernetes with DevOps SDLC Process

![Project Thumbnail](https://github.com/BSatishSutar/Maven-Project/assets/40925459/e3f5de0e-ab19-4995-83e8-018402ecb759)

This project exemplifies the deployment of a Java web application using Docker and Kubernetes, within the framework of a comprehensive DevOps Software Development Life Cycle (SDLC) process. The primary objective of the project is to provide a practical demonstration of establishing a robust deployment pipeline for a Java-based web application within a containerized environment.

## Project Highlights

- Leverages Docker for containerization, ensuring consistent and portable deployment environments.
- Harnesses the capabilities of Kubernetes for orchestration, guaranteeing scalability, load balancing, and autonomous recovery features.
- Embraces a DevOps SDLC process, seamlessly integrating continuous integration, continuous delivery, and automation principles.
- Illustrates optimal practices for configuring deployment pipelines, refining resource allocation, and enhancing the efficiency of software delivery.
- Offers insights into fostering effective collaboration between development and operations teams through a DevOps approach.
- Serves as a valuable learning resource for developers, DevOps engineers, and individuals interested in modern deployment methodologies.

## Prerequisites

Prior to beginning the project, it is essential to ensure the installation of the following prerequisites:

1. An EC2 instance, utilizing either the 'Ubuntu AMI' or an alternative AMI according to your preference. Additionally, opt for an 't2.medium or higher' instance type.
2. Docker software.
3. Minikube.
4. kubectl.

You can set up each of these prerequisites by following the step-by-step instructions provided below. These instructions are tailored for the Ubuntu AMI.

# Installation Steps

## Docker Installation

```bash
sudo apt-get update
sudo apt-get install docker.io -y
sudo usermod -aG docker $USER && newgrp docker
```

## Minikube & Kubectl Installation

```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
sudo install minikube-linux-amd64 /usr/local/bin/minikube

sudo snap install kubectl --classic
minikube start --driver=docker
```
## Contribution

Contributions to this project are highly appreciated! If you have suggestions, bug reports, or enhancements in mind, please don't hesitate to open an issue or submit a pull request on the GitHub repository.

## License

This project is licensed under the [Apache License 2.0](link-to-license).
