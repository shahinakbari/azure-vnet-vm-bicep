# Azure Virtual Network + Virtual Machine Deployment using Bicep

This project demonstrates how to deploy a secure and basic network infrastructure in Microsoft Azure using Bicep.  
It includes a Virtual Network, a Subnet with a Network Security Group (NSG), a Public IP, and a Virtual Machine (VM).

## 🧱 Technologies Used

- Azure Bicep
- Azure CLI
- Virtual Network (VNet)
- Network Security Group (NSG)
- Virtual Machine (Windows Server)
- Infrastructure as Code (IaC)

## 🚀 Deployment Steps

1. **Create Resource Group**
```bash
az group create --name vnet-rg --location westeurope
