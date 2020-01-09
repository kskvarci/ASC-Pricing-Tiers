# Multi-NIC Virtual Machine Creation using Two Subnets

This template will toggle the ASC tier settings for currently available resources.

## Tips

1. Within the parameters file set each resource type to "Free" or "Standard".
2. If deploying with CLI, be sure to use "az deployment create" and note "az group deployment create" as this deployment needs to take place at the subscription level and not at a resource group.
3. example: az deployment create --template-file azuredeploy.json --location "East US 2" --name "ASC" --parameters azuredeploy.parameters.json


