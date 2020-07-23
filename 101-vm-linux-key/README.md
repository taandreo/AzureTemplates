# Generic Linux Virtual Machine

Parameter         | Suggested value     | Description
:--------------- | :-------------      |:---------------------
**vmName** | The name of your Virtual Machine | The name of you Virtual Machine.
**adminUsername** | adminusername | Usernames can be a maximum of 20 characters and cannot end in a period (".").
**adminKey** | SSH Key | Public SSH key used to connect to the host.
**VmSize** | Standard_B1ls | The size of the VM.
**virtualNetworkName** | vNet | Name of the VNET
**subnetName** | subnet | Name of the subnet in the virtual network
**linuxImage** | Linux VM | The linux version for the VM. This will pick a fully patched image of this given distro version.
