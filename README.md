# azure-iaas
Azure Workshop "Valis v0.1"

---------------
Template "Azure-IaaS-VM.json"
---------------
az group deployment create --template-uri https://raw.githubusercontent.com/MadarsSmits/azure-iaas/master/Azure-IaaS-VM.json --verbose --resource-group valis --debug

- valis-VM1 VM
- valis-VM1 OS Disk
- valis-VM1 NIC
- valis-VM1 Public IP
- valis-VM1 NSG
- valis-VM1 VNET
- valis-VM1 Extention (Installs IIS Web Server + Management)