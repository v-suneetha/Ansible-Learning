🔸 PROJECT: CI/CD Integration with Ansible
🧩 Problem Statement (Real-World Scenario)

A company wants to automate application deployments. Currently:

Developers manually deploy code to servers
No consistency across environments
High risk of downtime

👉 The goal is to build a CI/CD pipeline that automatically deploys applications using Ansible whenever code is pushed.

🎯 Objective

You will build a pipeline using:

Jenkins OR GitHub Actions
Ansible for deployment
Dynamic or static inventory

Pipeline stages:
Build
Test
Deploy (Ansible)


🏗️ Architecture
Developer → Git Push → CI/CD Tool → Ansible → Target Servers


Prerequisites

Run Jenkins via WAR file (works in WSL)

This bypasses APT completely.

🔧 Step 1: Install Java
sudo apt update
sudo apt install openjdk-17-jdk -y

📥 Step 2: Download Jenkins manually
wget https://get.jenkins.io/war-stable/latest/jenkins.war

▶️ Step 3: Run Jenkins
java -jar jenkins.war

🌐 Access
http://localhost:8080

🔑 Get password
cat ~/.jenkins/secrets/initialAdminPassword