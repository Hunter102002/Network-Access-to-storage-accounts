# Network Access to Storage Accounts

## Objective

The Azure Storage Account Network Access Configuration project aimed to configure network access to an Azure Storage Account from both a virtual machine (VM) hosted in Azure and an on-premises network. The goal was to ensure secure and controlled access to storage resources, allowing authorized applications and users to interact with the storage account while restricting access from unauthorized sources. 

### Skills Learned

- Configuration of network security groups (NSGs) to control inbound and outbound traffic to Azure resources.
- Integration of Azure Virtual Network (VNet) with Azure Storage Account for private access.
- Establishment of hybrid network connectivity between Azure and on-premises networks using Azure Virtual Network Gateway and VPN Gateway.
- Configuration of network routing and DNS settings to ensure seamless communication between Azure resources and on-premises networks.
- Implementation of network security best practices to protect data in transit and prevent unauthorized access.

### Tools Used

-Azure Portal or Azure CLI for configuring network access control settings.
- Azure Storage Explorer or Azure PowerShell for interacting with Azure Storage Account resources.
- Azure Virtual Network Gateway and VPN Gateway for establishing hybrid network connectivity.
- Network monitoring tools for monitoring network traffic and security events.

## Steps
Create a Virtual Network![Screenshot 2024-05-13 at 9 58 55 AM](https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/5ea6c76c-4945-44bf-868a-ed6af7fba5f0)

Create a storage account with a private endpoint![Screenshot 2024-05-13 at 10 01 14 AM](https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/40b7fbc2-1dbd-4e47-a5b8-dee468edf1b4)

Verify creation of storage account and private endpoint![Screenshot 2024-05-13 at 10 07 55 AM](https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/dbeec6ca-c40f-440b-bf94-11348be1c880)

Create a VM![Screenshot 2024-05-13 at 10 17 37 AM](https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/d044fef2-4d21-4c09-92e6-202981e59b40)

Log into VM with on prem machine![Screenshot 2024-05-13 at 10 19 25 AM](https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/189fa76f-6967-466e-abba-c451ed208d47)

Verify Creation with Powershell<img width="1469" alt="Screenshot 2024-05-13 at 10 23 13 AM" src="https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/c948a612-ed97-404a-8ab2-c63f40480d7a">

Turn off enhanced security for admins on VM<img width="1470" alt="Screenshot 2024-05-13 at 10 24 31 AM" src="https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/d4c5260d-4bf0-4bd0-a0ac-7409344689f3">

Connect to storage account with the connection string<img width="1191" alt="Screenshot 2024-05-13 at 10 27 18 AM" src="https://github.com/Hunter102002/Network-Access-to-storage-accounts/assets/98543129/8b6e3436-9800-4de9-8f77-7698d1b4ad09">

