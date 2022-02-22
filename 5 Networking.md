# Networking

## Virtual Networks
Virtual Networks(VNet) enables Azure resources such as Virtual Machines to securly communicate with each other, the internet and on prem networks.
- Address Space is the range of IP Addresses available in a VNet. Each Resource in the VNet will get a unique IP Address within the IP Range of the VNet
- Subnets allow you to segment the VNet in to one or more subnet. This allows you to group resources into the same subnet making it easier to have an overview. It also makes it easier to allocate addresses to resources on a smaller subnet. Subnets make VNets more secure by allowing you to use network security groups for individual subnets
- VNets belong to a single region and every resource on a VNet must be in the same region


## Load Balancer
Load Balancer distributes new inbound flows that arrive on the Load Balancers frontend to backend pool intances, according to rules and health probes

## VPN Gateway
A VPN Gateway allows you to securely communicate with Azure Resources and your on premise network


## Application Gateway
An Application Gateway is a higher level load balancer that works on HTTP requests of the traffic instead of IP address and port.
Traffic from specific adresses can routed to specific machines
Aupports Auto Scaling , end to end encryption, zone redundency and multi site hosting

## Content Delivery Network
Content Delivery Network (CDN) is a distributed network of servers that can deliver web content close to users

[back](ReadMe.md)