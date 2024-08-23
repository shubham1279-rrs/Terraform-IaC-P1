# Terraform Azure Infrastructure Setup

This Terraform project provisions a basic Azure infrastructure, including a resource group, virtual network, subnet, network interface, Windows virtual machine, and an Azure service plan.

## Overview
The project defines and deploys the following resources:

Resource Group: A container that holds related resources for an Azure solution.
Virtual Network (VNet): Enables resources to securely communicate with each other.
Subnet: A segment of the VNet.
Network Interface (NIC): Connects the VM to the VNet.
Windows Virtual Machine (VM): A virtual machine running Windows Server.
Service Plan: Used for managing an App Service.



## Prerequisites
Before you begin, ensure you have the following:

Terraform: Installed on your local machine. The required version is >= 1.0.
Azure CLI: Installed and configured to authenticate to your Azure account.
Azure Subscription: Ensure you have the necessary permissions to create resources.


## Installation

1. Clone the repository:
git clone https://github.com/your-username/your-repo-name.git,
cd your-repo-name

2. Initialize Terraform: Initialize the Terraform configuration directory:- terraform init


3. Review the plan: Ensure the resources that Terraform will create are correct:- 
terraform plan

4. Apply the configuration: Deploy the infrastructure:- terraform apply
  



## Usage

Managing the infrastructure: You can manage the infrastructure by modifying the .tf files and running terraform apply to apply the changes.
Destroying the infrastructure: To remove all resources created by Terraform, use
terraform destroy