# End-to-End Azure Data Engineering Project

## Execution Instructions:

1. Provision resources:
  a. Assuming Subscription is already provisioned, we can start with the Resource Group. Resource group contains all the provisioned resources in one place.
  b. Provision your Vnet. During provisioning a lot a subnet for both private and public facing traffic. Both subnets will be used for the Azure Data Factory, Azure Databricks and Azure Synapse Analytics.
  c. Provision your DatalakeGen2 Storage and consequently Azure Blob Storage, with the Vnets in mind. 
  *insert images of blob storage networking config*
  d. 
2. Modify Vnets
3. Check connectivity
4. Execute codebase
5. Create Dashboard