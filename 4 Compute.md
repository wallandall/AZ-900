# Compute

## Virtual Machines
Virtual Machines are at the core of Azure compute and are widely used
- Pricing for VMs is calculated Hourly
- You need to maintain the OS and Applications (IaaS)

### Create a Virtual Machine:

1. [Log In to the Azure Portal](https://portal.azure.com/)
   1. Enter your username and password
   2. In the Welcome to Microsoft Azure message box, click Maybe later.
2. Create a Virtual Machine
   1. On the Azure Portal home page, click Create a Resource.
   2. Search for Virtual Machine and create one.
   3. In the Basics tab, configure the following settings:
       1. Resource group: (Select an existing resource group from the dropdown or create a new resource group)
        2. Location: Use the same region as your Resource Group's region.
        3. Virtual machine name: (Give the virtual machine a unique name.)
        4. Image: Select the Image you want for your Server
        5. Set the Size e.g: Standard DS1_v2
        6. Enter a username for the VM e.g: something-admin
        7. Enter the password for the VM e.g: Admin123456!
        8. Confirm password: Admin123456!
   4. Click Next : Disks >.
      1. In the Disks tab, configure the following settings:
      2. OS disk type: Premium SSD
   5. Click Next : Networking >.
      1. If for some reason port 3389 is not automatically filled in, for "Public Inbound Ports" select "Allow selected ports" and then for "Selected Inbound Ports" use the drop to choose "RDP 3389"
   6. Click Next : Management >.
   7. Click Next : Advanced >.
   8. Click Next : Tags >.
   9. Click Next : Review + create >.
   10. Click Create.
   11. Click the notifications icon at the top of the screen to monitor the deployment.
Wait a few minutes for the status to change to Your deployment is complete.
3. Connect to the Virtual Machine
   1. Click All resources in the left sidebar.
   2. Click the name of our virtual machine to open it.
   3. Click Connect at the top of the page.
   4. Click Download RDP File. Note: You have to wait a few minutes before you will be able to connect even if the VM shows as ready.
   5. Execute the RDP file either from the folder is was downloaded to, or your browser if it allows it Quick Note: If you are on a Mac, make sure you are using the latest remote desktop tool which can be found at this URL. https://apps.apple.com/app/microsoft-remote-desktop/id1295203466?mt=12
   6. In the Enter your credentials menu, enter the following:
   7. User name: something-admin
   8. Password: Admin123456!
   9. Click OK.
   10. Click Yes.
4. Turn Off the Virtual Machine
   1. Go back to the Azure Portal in your browser.
   2. In the virtual machine menu, click Stop.
   3. Click OK.
   4. Wait a few moments, and refresh the menu until the status changes to Stopped (deallocated).

## Scale Sets
[Azure Scale Sets](https://docs.microsoft.com/en-us/azure/virtual-machine-scale-sets/overview) allow you to create and manage a group identical load balanced VMs to ensure high availability. 
-


## App Services
App Services are full managed platform which means the servers, network and storage are managed by Azure. App Services come in 3 different categories:
- Web Apps: Websites and online applications hosted on Azures managed platform
  - Can run both Windos and Linux VMs
  - Supports .Net, Java, Node.js, Python and Ruby
  - Allows Azure integration for easier Deployment
  - Supports Autoscaling and load balancing
- WebApps for Cantainers : Deploy and run conainerized applications in Azure
  - All dependencies are shipped inside the container
  - Deploy anywhere whith a consistent experience 
  - Reliability between environments
- API Apps expose and connect your data backend

## Azure Container Instances
[Azure Containers Instances](https://docs.microsoft.com/en-us/azure/containers/) is the primary service for running container applications or services. 


## Azure Kubernetes Services
[Azure Kubernetes Service](https://docs.microsoft.com/en-us/azure/aks/) allows you to manage containers with Kubernetes.
- Reuse you container architecture by managing it in Kubernetes making setup quicker .
- You do not need to worry about infrastrucutre and hardware 

## Azure Virtual Desktop
Azure Virtual Desktop is a completely virtualised version of Windows
- Reuse windows 10 licenses which will reduce cost
- Multiple users can use the same VM
- Can be used anywhere and from any device 
- Use Azure Storage to secure data

## Functions
[Azure Functions](https://docs.microsoft.com/en-us/azure/azure-functions/) are the smallest compute service on Azure and provides a single compute function when called or invoked via a web address. Azure Functions can talk to other Azure services or perfomr functions that run once and stop.


[back](ReadMe.md)