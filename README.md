Roboshop – Ansible Deployment

This project contains Ansible playbooks to automate the deployment of the Roboshop microservices application on AWS EC2. All components are installed, configured, and started automatically using Ansible tasks.

🚀 Overview

Fully automated setup of all Roboshop microservices

Installs required runtimes: NodeJS, Python, Maven

Configures MongoDB and Redis databases

Sets up systemd services for each microservice

Configures Nginx reverse proxy for the frontend

🧩 Tech Stack

Ansible

AWS EC2

Linux (CentOS / RHEL / Amazon Linux)

NodeJS, Python, Maven

MongoDB, Redis

Nginx

▶️ How to Run
ansible-playbook -i inventory roboshop.yml

📂 Files Included
inventory
roboshop.yml
frontend.yml
user.yml
cart.yml
catalogue.yml
payment.yml
shipping.yml

⭐ Highlights

Simple and clean Ansible automation

Easy to execute with a single playbook command

Database schemas load automatically

End-to-end deployment without manual steps
