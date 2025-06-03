# 🌟 Projects

### <img src="./images/aws.png" width="20"> <img src="./images/terraform.png" width="20"> **AWS + Terraform Projects**
- [x] **[3-tier application deployment with github-actions CICD](https://github.com/danielFarag/aws-3-tier-cicd)**: Provision 3 tier application infrastructure with public/private subnets, security groups, NAT and SSM for configuration and Implement a simple CI/CD using Github actions.
- [x] **[AWS CSV Pipeline using Glue, s3 and rds](https://github.com/danielfarag/aws-csv-pipeline-glue-s3-rds)**: automated Extract, Transform, Load (ETL) pipeline using RDS (MySQL) as a data target, AWS Glue for data cataloging and transformations, Amazon S3 for data staging and script storage, and AWS Lambda and CloudWatch Events for workflow orchestration and notifications.
- [x] **[Jenkins Master-Slave Architecture on AWS](https://github.com/danielfarag/jenkins-aws-private-master-ssm-slaves)**: This project deploys a Jenkins master-slave architecture on AWS using Terraform. It leverages AWS Systems Manager (SSM) for secure access to instances and automates the setup of Jenkins agents using auto-scaling groups, including automatic registration of new nodes and the capability to manage disconnected nodes.
- [x] **[EC2 Slack Notifier](https://github.com/DanielFarag/ec2-slack-notifier)**: Monitor EC2 instance state changes using AWS Lambda & EventBridge, then send alerts to Slack via webhook.

### <img src="./images/gcp.png" width="20"> <img src="./images/terraform.png" width="20"> **GCP + Terraform Projects**
- [x] **[Automated GKE Deployment with GitOps](https://github.com/danielfarag/iti-gke-gitops)**:: This project provides a comprehensive Terraform and GitHub Actions solution to deploy a GKE cluster and manage its applications (Helm charts, ArgoCD Applications, k8s resources ) using a GitOps workflow.
- [x] **[gcp-secure-gke-network](https://github.com/danielfarag/gke-private-subnet-deployment)**:: Provision a highly secure GCP infrastructure featuring a private GKE cluster within a restricted subnet, an isolated management subnet with NAT, and public exposure via an HTTP Load Balancer, all configured with Terraform.

### <img src="./images/k8s.png" width="20"> **Kubernetes Projects**
- [x]  **[Ingress-Like operator: Nginx Proxy](https://github.com/DanielFarag/k8s-ingress-controller)**: A custom controller that build a simple nginx proxy server.
- [x]  **[Custom Resources for Vault Integration](https://github.com/danielfarag/k8s-vault-controller)**: A custom Kubernetes controller that syncs secrets from HashiCorp Vault to Kubernetes Secrets using CRDs.

### <img src="./images/docker.png" width="20"> **Docker Projects**
- [x]  **[Dockerize a Laravel Project](https://github.com/DanielFarag/dockerize-laravel-demo)**: Containerize Laravel/Mysql/PhpMyadmin/Nginx/Vue application.  
- [x]  **[Dockerize a Node Project](https://github.com/DanielFarag/presentation-demo)**: Containerize a Node/Mysql/PhpMyadmin/Nginx/Angular application.  


### <img src="./images/ansible.png" width="20"> **Ansible Projects**
- [x] **[Bastion SSH Setup with Terraform & Ansible](https://github.com/DanielFarag/aws-bastion-ssh-setup)**: This project provisions an AWS environment using Terraform and configures SSH access using Ansible. Automates SSH key generation and distribution to allow transparent access to private hosts via the bastion
- [x]  **[Jenkins Ansible Playbook](https://github.com/danielfarag/ansible-jenkins-ec2)**: This Ansible project automates the installation of Jenkins and Java on Debian or RedHat-based systems. It includes role-based tasks and supports installing Jenkins plugins defined in variables.  
- [x]  **[iti.jump Ansible Plugin](https://github.com/danielfarag/jump-ansible-plugin)**: This Ansible plugin simplifies the process of connecting to private EC2 instances through a bastion host. It automates SSH config generation and public key distribution, allowing seamless SSH access from a bastion to private instances..  


### <img src="./images/programming.webp" width="20"> **Programming Projects**
- [x]  **[Ticket Management System (Laravel)](https://github.com/danielfarag/ticket-management-system)**: Provides functionalities like creating, listing, and deleting tickets and provide support platform for agents and administrators.
- [x]  **[Bookstore (Node.js)](https://github.com/DanielFarag/bookstore)**: Develop a CRUD app consists of Books, Users, Reviews for managing library data using Express.js.
- [x]  **[DBMS (Bash)](https://github.com/DanielFarag/dbms-bash)**: Provides basic functionalities like creating, listing, and deleting databases, as well as managing tables.
