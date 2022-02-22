# Cloud Concepts
Cloud computing is the ondemand availability of computing resources split into 3 categories:
- Compute 
- Networking 
- Storage

Cloud service providers provide these services via datacenters accross the globe. Advantages of cloud computing includes low cost, ease of adoption and almoat unlimted resources.

## The language of cloud computing
- High Availability, resources are available at the click of a button
- Fault Tolerance describes how Azure will ensure you have zero downtime for services provided by Azure
- Disaster Recovery uses time-to recovery and recovery point metrics to recover from disasters such as tornadoes, floods etc.
- Scalability is the ability scale resources out, up or scale down. 
- Elasticity is the ability to quickly expand or decrease computing resources
- Agility is the ability to rapidly develop, test and launch software applications that drive business growth.

## The Economy of Cloud Computing
One of the major reasons for using cloud resources is the cost associated with cloud computing
- Capital Expenditure is the money spent by a business or organisation on aquiring or maintaining fixed assests such as land, building and equipment. Example Server and networking equipment
- Operational Expenditure is an ongoing cost for running a product, business or system on a day to day basis including annual costs . Examples include electricity or the cost of running a website.
- Cloud computing reduces IT expenditure by reducing CapEx costs 
    - no large upfront investments
    - Pay only for the resources you use 

## Cloud Service Models
- Infrastrucutre as a Service(IaaS) examples include VMs, VNet and Storage:
    - Organisations have complete control of the infrastrucutre 
    - Dynamic and flexible.
    - Cost varies depending on consumption
    - Services high cscalability
    - Multiple users share single piece of hardware
- Platform as a Service (PaaS) examples include App Services, Azure CDN, Cosmo DB
    - Resources are virtualised and can easily be scaled up or down as needed.
    - Services often assist with the development , testing and deployment of Apps
- Software as a Service (SaaS) eg M365
    - Managed from a central location
    - Hosted on  a remote server
    - Users are not responsible for hardware or software updates
- Shared Responsibility means that MS is responsible for certain areas and you are responsible for other areas when maintaining cloud resources e.g:

![Shared Responsibility](img\SharedResponsibility.png)

## Azure Marketplace
Azure Marketplace is an integral part of Azure and offers Solutions and Services, Azure App, and is easy to integrate and publish your own Apps.

## Cloud Architect Models
When considering cloud architecture there are thre Models:
- Private Cloud
    - Private Cloud is maintained by an organisation and is only accessible to the organisation that maintains it
        - The organisation must maintain the infrastrucutre but has full controll of their resources.
        - It is more secure as the organisation can define their own security rules
- Public Cloud are commercial cloud providers that offer their services to the public e.g:
    - AWS
    - GCP
    -Azure
- Hybrid Cloud is a combination of Public and Private Cloud

[back](ReadMe.md)