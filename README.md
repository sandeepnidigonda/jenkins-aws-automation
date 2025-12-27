# CI/CD Automation: Jenkins + AWS EC2 + GitHub Webhooks

I’ve successfully set up a fully automated CI/CD trigger to eliminate manual builds! 🚀

## 🛠 Project Overview
This project focuses on event-driven automation. Every time code is pushed to this repository, GitHub sends a signal via Webhooks to a Jenkins server hosted on AWS, which immediately triggers the build process.

## 🏗 Infrastructure & Tools
* **AWS EC2:** Hosted the Jenkins server on a Linux instance.
* **Jenkins:** Managed the build automation.
* **GitHub Webhooks:** Acted as the bridge between the code and the server.
* **Linux:** Server configuration and security management.

## 🔑 Key Learnings
* Configuring **AWS Security Groups** (Port 8080 for Jenkins).
* Managing Linux server environments.
* Setting up Webhook payloads and secret tokens for secure communication.
