
# Project: Complete Infrastructure as Code (Terraform + Ansible)
Implementing Infrastructure as Code (IaC) principles through the use of Terraform and Ansible.

---------------


## Goal:

Apply **Infrastructure as Code (IaC)** concepts using **Terraform** and **Ansible** in a fully working and (hopefully) realistic personal project.



## Why this project?

Provisioning cloud resources manually through the AWS console is inefficient and error-prone. With **Terraform**, you can define your infrastructure as code — enabling versioning, reuse, and automation.



### DevOps best practices in action

This project simulates a real-world production scenario where:

* Infrastructure is provisioned automatically (IaC)
* The server is configured automatically (Configuration as Code)
* The entire environment can be scaled, destroyed, or replicated with a single command



### Create a reusable foundation for future projects

The repository is designed for reuse and growth:

* Clear separation between provisioning (Terraform) and configuration (Ansible)
* Modular structure, adaptable to other providers
* Extendable to include CI/CD, observability, security, and more



### Consolidate knowledge across multiple tools

Tools used in this project:

* **Terraform**: to provision AWS resources
* **Ansible**: to automatically configure the EC2 instance
* **AWS**: as the cloud infrastructure provider



## What’s included

* Provisioning of VPC, Subnet, Security Group, and EC2 using **Terraform**
* Automatic server setup (e.g., **Nginx**) using **Ansible**
* Well-documented and organized structure for learning or production use



## Next steps

* Modularize Terraform code
* Add an Application Load Balancer (ALB)
* Create a managed RDS database
* Automate deployment using CI/CD ( GitHub Actions + ArgoCD)


