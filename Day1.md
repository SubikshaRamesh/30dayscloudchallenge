# Azure Virtual Network and Virtual Machine Setup Guide
 In Azure, Virtual Network (VNet) allows you to create a secure, private network in the Azure cloud. It provides the 
 foundation for securely connecting Azure resources like virtual machines and subnets.
 It also allows you to define IP address range.

 A subnet (subnetwork) is a smaller division of an Azure Virtual Network (VNet) that helps organize resources and improve traffic management.
 Subnets allow you to divide the VNet into smaller segments with specific IP ranges.

A Virtual Machine (VM) is a software emulation of a physical computer. In Azure, VMs allow you to run applications and services as if they were running on a physical server, but with the added benefits of scalability, flexibility, and cost-effectiveness.

This will help you to create a VNet,subnet and a VM.Let's get started.

# Task 1: To create a Virtual Network and set up a Subnet
1.Open the azure portal and look for the menu bar.

2.Click on "Virtual network".

3.Hit the "Create" button and start creating your VNet.

4.Create a new Resource group.

5.Name the virtual network and choose a region.(eg: South India)

6.Click on "Create new IP Address" to define address space.

7.To create a subnet under subnet section click on "Add subnet".

8.Name the subnet.(eg:Mysubnet).

9.Now,finally click on "Review + create".


# Task 2: To create a Virtual Machine on the Subnet

1. In Azure portal,search for Virtual Machine and click on "Virtual Machine".

2. Click on "Create" and select Azure Virtual Machine.

 3.Fill in the Required Information:

   Select Subscription: Choose the same subscription you used before.

   Select or Create Resource Group: Pick your resource group again.

   Virtual Machine Name: Give your VM a friendly name.

   Region: Select the same region as your virtual network.

   Image: Choose the OS for your VM.

   VM Architecture: Stick with the default x64.

   Size: Select a size based on what you’ll be doing.

4.Under the "Admin Account" section:

   Authentication Type: Choose "Password".

   Username: Create a username for your VM (e.g., adminUser).

   Password: Enter a strong password and confirm it.


5.Under the "Networking" section:

   Virtual Network: Select your VNet (MyVNet).

  Subnet: Choose the subnet you just created (MySubnet).

  You can adjust public IP and NSG settings as needed. 

6.Click "Review + create".

# Connect to Virtual Machine
1.Click on your new VM.

2.Hit the "connect" button at top.

3.Choose "RDP" if you're on a windows VM and download the "RDP file".

4.Open your RDP and enter your credentials.

5.Next confirm connection by clicking "yes".

6.Now your VM is ready.
