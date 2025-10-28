# Azure Network Layer using Terraform

## 📘 Overview
This project defines a **network layer** on Microsoft Azure using **Terraform**. It provisions:
- Resource Group
- Virtual Network (VNet)
- Subnet
- Network Security Group (NSG)
- NSG association to the subnet

## 🧠 Why Terraform + Azure
Terraform provides Infrastructure as Code (IaC), making it:
- **Repeatable:** Same config can deploy multiple environments.
- **Scalable:** Easily extend network or integrate with compute modules.
- **Auditable:** Stored in GitHub with version control.

## ⚙️ Requirements
- Terraform >= 1.13.4
- Azure CLI
- Azure Subscription

## 🚀 Deployment Steps

1. Clone this repo:
   ```bash
   https://github.com/HermanBide/Network_Layer-with-Terraform/tree/main/Azure_network_terraform
   cd azure-network-terraform
