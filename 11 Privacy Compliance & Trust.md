# Privacy, Trust and Compliance

## Governance
Governance in Azure is one aspect of Azure Management. [This article](https://docs.microsoft.com/en-us/azure/governance/azure-management) covers the different areas of management for deploying and maintaining your resources in Azure.

Management refers to the tasks and processes required to maintain your business applications and the resources that support them. Azure has many services and tools that work together to provide complete management. These services aren't only for resources in Azure, but also in other clouds and on-premises. Understanding the different tools and how they work together is the first step in designing a complete management environment.

The following diagram illustrates the different areas of management that are required to maintain any application or resource. These different areas can be thought of as a lifecycle. Each area is required in continuous succession over the lifespan of a resource. This resource lifecycle starts with the initial deployment, through continued operation, and finally when retired.

- [Azure Policy](https://docs.microsoft.com/en-us/azure/governance/policy/overview)
- [Azure Management Groups](https://docs.microsoft.com/en-us/azure/governance/management-groups/overview)
- [Azure Blueprints](https://docs.microsoft.com/en-us/azure/governance/blueprints/overview)
-[Azure Resource Graph](https://docs.microsoft.com/en-us/azure/governance/resource-graph/overview)
-[Azure Cost Management](https://docs.microsoft.com/en-us/azure/cost-management-billing/cost-management-billing-overview)

## Azure Monitor
[Azure Monitor](https://docs.microsoft.com/en-us/azure/azure-monitor/overview) helps you maximize the availability and performance of your applications and services. It delivers a comprehensive solution for collecting, analyzing, and acting on telemetry from your cloud and on-premises environments. This information helps you understand how your applications are performing and proactively identify issues affecting them and the resources they depend on.

## Azure Service Health
Azure offers a suite of experiences to keep you informed about the health of your cloud resources. This information includes current and upcoming issues such as service impacting events, planned maintenance, and other changes that may affect your availability.

[Azure Service Health](https://docs.microsoft.com/en-us/azure/service-health/overview) is a combination of three separate smaller services.

- Azure status informs you of service outages in Azure on the Azure Status page. The page is a global view of the health of all Azure services across all Azure regions. The status page is a good reference for incidents with widespread impact, but we strongly recommend that current Azure users leverage Azure service health to stay informed about Azure incidents and maintenance.

- Service health provides a personalized view of the health of the Azure services and regions you're using. This is the best place to look for service impacting communications about outages, planned maintenance activities, and other health advisories because the authenticated Service Health experience knows which services and resources you currently use. The best way to use Service Health is to set up Service Health alerts to notify you via your preferred communication channels when service issues, planned maintenance, or other changes may affect the Azure services and regions you use.

- Resource health provides information about the health of your individual cloud resources such as a specific virtual machine instance. Using Azure Monitor, you can also configure alerts to notify you of availability changes to your cloud resources. Resource Health along with Azure Monitor notifications will help you stay better informed about the availability of your resources minute by minute and quickly assess whether an issue is due to a problem on your side or related to an Azure platform event.

## Compliance

[Azure compliance manager](https://docs.microsoft.com/en-us/microsoft-365/compliance/compliance-manager?view=o365-worldwide) provides recommendations on how to meet industry compliance.



[back](ReadMe.md)