# Azure Architecture

## Azure Regions
[Azure regions](https://docs.microsoft.com/en-us/azure/availability-zones/az-overview) are a set of datacenters deployed withing a latency-defined perimeter and connected through a dedicated regional low-latency network.
- A set of datacenters means each region has more than 1 data center which is a physical location 
- Latency defined perimiter means that the datacenters are not too far from each other 
- Regionalk low-latency network means a high speed connection between centers in each in the region
- How to choose a region:
    - Choose a region closest to your users to minimize latency
    - Choose a region that includes the services you need as not all services are available in all regions
    - Pricing differes between region

## Availability Zones 
Availability Zones are unique pyhical locations in an Azure Region. 
- Each Zone has its own power, cooling and networking.
- Each Region has a minimum of three zones.

## Resource Groups and the Azure Resource Manager
[Azure resource regroups](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/manage-resource-groups-portal) are containers for holding resources in Azure, and all resources need to be inside a resource group.
- Each resource can only exisit in a single resource group.
- Resources can be added, moved or removed fromn resource groups
- Resources from multiple regions can be in one resource group
- You can use resource groups to manage access to resources.
- Resources can intreract with resources in different resource groups

# Azure Resource Manager (ARM)
ARM is the single entry point for managing resources in Azure 
- You can deploy , manage and monitor resources as a group
- Deploying resources from various tools e.g: Azure Portal, Azure CLI, Azure PowerShell etc, will always have the same sonsistent state.
- Define dependencies between resources.
- ARM makes it easy to assign access rights to users
- Resources can be tagged

[back](ReadMe.md)