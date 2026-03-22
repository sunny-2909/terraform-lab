# Terraform Lab - Infrastructure as Code

## Objective
This lab demonstrates Infrastructure as Code (IaC) using Terraform. It covers creating, managing, and automating infrastructure using configuration files.

---

## Tools Used
- Terraform
- Docker
- Git
- GitHub

---

## Day 1: Introduction to Terraform
- Installed Terraform CLI
- Created a file using Terraform
- Used terraform init, plan, apply
- Used variables and outputs

---

## Day 2: Variables and Configurations
- Used input variables
- Created dev.tfvars and prod.tfvars
- Applied different configurations using variable files

---

## Day 3: Managing Containers with Terraform
- Used Docker provider
- Pulled nginx image
- Created container
- Accessed service on localhost:8080

---

## Day 4: Terraform Modules
- Created reusable module
- Used module to create multiple containers
- Ran containers on ports 8081 and 8082

---

## Day 5: Automation and Validation
- Created GitHub workflow
- Ran terraform fmt, validate, and plan automatically

---

## Conclusion
This lab helped understand how infrastructure can be managed using code, making deployments faster, consistent, and automated.