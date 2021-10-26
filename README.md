
# Azure Synapse on Private Endpoints

Azure Synapse Analytics is a limitless analytics service that brings together data integration, enterprise data warehousing, and big data analytics. 

It gives you the freedom to query data on your terms, using either serverless or dedicated resources—at scale. Azure Synapse brings these worlds together with a unified experience to ingest, explore, prepare, manage, and serve data for immediate BI and machine learning needs..

# Synapse deployment on Azure Private Endpoints 

Azure Private Endpoint is a network interface that connects you privately and securely to a service powered by Azure Private Link. Private Endpoint uses a private IP address from your VNet, effectively bringing the service into your VNet. 

Synapse uses a managed VNET / Subnet and exposes private endpoints in customers’ vnets as needed. Since the VNETs belong to Microsoft and are managed, The VNETs are isolated therefore we require private endpoints for PaaS services in Azure.


## Target audience

- Infrastructure Architect
- Data Engineers
- Data Architects

# Synapase Architecture deployed on Private Endpoints
![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/azure-synapse-detailed-diagram.png?raw=true)

# Synapase Workspace
![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/synapse-workspace.png?raw=true)

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

![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/Description.PNG?raw=true)

- Add for modified [Template.json](Template.json) and save it

![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/template_code.PNG?raw=true)

- Select the newly added template and click deploy

![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/deploy.PNG?raw=true)

- Fill out the blanks with your details and click purchase

![alt image](https://github.com/kamaddal/Managed-Synapse_deployment/blob/main/purchase.PNG?raw=true)

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



