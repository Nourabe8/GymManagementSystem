# AutoFlow 🚀

AutoFlow is a fully automated GitOps pipeline designed to simplify deployments, enhance security, and improve visibility in Kubernetes environments.

## 💡 Motivation

In fast-paced DevOps teams, it's common to face challenges like:

- 🔁 Manual deployments that are time-consuming  
- 🔐 Insecure access control to Kubernetes resources  
- 📡 Lack of visibility into deployment events  

AutoFlow addresses these pain points by automating the entire workflow — from code push to deployment — with real-time notifications and access control.

## ⚙️ Features

- • **GitOps Workflow** with GitHub + Argo CD  
- • **Automated Deployments** on every code push  
- • **RBAC Integration** using Kubernetes ServiceAccounts  
- • **Slack Notifications** via n8n for real-time deployment alerts  
- • **Declarative Configuration** and Infrastructure as Code (IaC) principles  

## 🧰 Tech Stack

| Tool           | Purpose                          |
|----------------|----------------------------------|
| Kubernetes     | Container orchestration          |
| GitHub         | Source control & GitOps trigger  |
| Argo CD        | Continuous deployment            |
| n8n            | Workflow automation & Slack alerts |
| RBAC           | Secure access using ServiceAccounts |

## 🚀 How It Works

1. Developer pushes code to GitHub
2. GitHub triggers Argo CD to sync the new configuration
3. Argo CD deploys the app to the Kubernetes cluster
4. n8n receives a webhook and sends a Slack notification

## 📁 Project Structure

