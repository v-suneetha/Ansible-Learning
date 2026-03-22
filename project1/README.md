# Ansible-Learning
🔹 PROJECT 1: Automated LAMP Stack Setup using Ansible
🧩 Problem Statement (Real-World Scenario)

A development team frequently needs new web servers to deploy internal applications. Currently, engineers manually install Apache, MySQL, and PHP on each server, which leads to:
Inconsistent configurations
Time-consuming setup
Human errors

👉 Your task is to automate the provisioning and configuration of LAMP stack servers using Ansible, ensuring consistency and repeatability.

🎯 Objective
By the end of this project, you will:
Provision a web server using Ansible
Install and configure:
Apache (web server)
MySQL (database)
PHP (runtime)

Deploy a sample PHP application
Ensure idempotency (safe re-runs)

🏗️ Architecture
1 Control Node (Ansible installed)
1 or 2 Target Nodes (managed servers)


Control Node → Ansible
Target Node(s) → Web Server(s)
