# Deployment of a Windows VM with OMS Extension

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-oms-extension-windows-vm%2Fazuredeploy.json" target="_blank">
    <img src="http://azuredeploy.net/deploybutton.png"/>
</a>
<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2Fazure-quickstart-templates%2Fmaster%2F201-oms-extension-windows-vm%2Fazuredeploy.json" target="_blank">
    <img src="http://armviz.io/visualizebutton.png"/>
</a>

This template allows you to deploy a Windows VM with the OMS extension installed and onboarded to a specified workspace. You may obtain the workspace ID and key by going to the Connected Sources tab in the Settings page in the OMS Portal or to the Direct Agent blade in the Azure portal.


Quick Test VM
.\Deploy-AzureResourceGroup.ps1 -ResourceGroupLocation 'East US 2' -ArtifactStagingDirectory 'provisioning-vms-via-oms' -ResourceGroupName 'AzureTest'

