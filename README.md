
# Azure Synapse on Managed Vnet

Azure Synapse Analytics is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. 

Here's what you can do when you run Azure Virtual Desktop on Azure:

It gives you the freedom to query data on your terms, using either serverless or dedicated resources—at scale. Azure Synapse brings these worlds together with a unified experience to ingest, explore, prepare, manage, and serve data for immediate BI and machine learning needs..

# Azure Manages Vnet Synapse deployments 

Azure landing zones are the output of a multisubscription Azure environment that accounts for scale, security governance, networking, and identity. Azure landing zones enable application migration, modernization, and innovation at enterprise-scale in Azure. These zones consider all platform resources that are required to support the customer's application portfolio and don't differentiate between infrastructure as a service or platform as a service.


## Target audience

- Infrastructure Architect
- Data Engineers
- Data Architect
- ![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/azure-synapse-detailed-diagram.png?raw=true)

# Product/Managed Endpoint Synapase architecture

The [Template.json](Template.json) Azure Resource Manager template will help you automatically deploy the diagram below, which includes:

example!!!

- Deploy a Azure Vnet or use vnet from existing handing zone.
- Deploy Azure Synapase studio.
- Create SQL Pools & Spark Pools .
- Create a Privatelink and assign & Plumb the Synapse services to Azure Vnet.



[Template.json](Template.json) can be modified to match your current infrastructure needs.

## Deploying an ARM Template using the Azure portal

- Visit https://portal.azure.com

Using the search bar on top type Templates

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/0c27bbe224b6c1e408883e4fd22b992d503549fd/Search.png?raw=true)

- Create a new template

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/8bd3fb167da7f7c76eb01954d73f1ce6948a9a41/create.png?raw=true)

- Give a name and a description to the template

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/8bd3fb167da7f7c76eb01954d73f1ce6948a9a41/Name%20and%20Description.png?raw=true)

- Add for modified [Template.json](Template.json) and save it

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/8bd3fb167da7f7c76eb01954d73f1ce6948a9a41/add%20code.png?raw=true)

- Select the newly added template and click deploy

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/8bd3fb167da7f7c76eb01954d73f1ce6948a9a41/Select%20and%20deploy%20template.png?raw=true)

- Fill out the blanks with your details and click purchase

![alt image](https://github.com/DavidArayaSanabria/AVDLandingZone/blob/8bd3fb167da7f7c76eb01954d73f1ce6948a9a41/Fill%20out%20the%20details%20and%20purchase.png?raw=true)

- Allow 30 minutes for the deployment to complete
- Peer your Hub and Spoke Virtual Networks as needed

## Azure services and related products

example!!
- Azure Virtual Networks
- Azure Managed Endpoints
- Azure Private links
- Azure Synapse

## Related references
example!!
- https://docs.microsoft.com/en-us/azure/synapse-analytics/security/how-to-create-managed-private-endpoints
- https://docs.microsoft.com/en-us/azure/virtual-network/tutorial-connect-virtual-networks-portal#peer-virtual-networks
- https://docs.microsoft.com/en-us/azure/virtual-desktop/safe-url-list#virtual-machines
- https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/ready/landing-zone/



