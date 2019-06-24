# Create Virtual Machine from gallery Image with Custom Extension and Availability Set


This template creates a Virtual Machine with:
- Selection of existing virtual network and subnet
- Monitoring Extension
	- Selection of log analytics workspace
- Custom Script Extension
	- Selection of storage account where the script is located
	- Command to execute the script
- Creation of new or selection of storage account for boot diagnostics
- Diagnostics Extension
	- Selection of the same storage account from boot diagnostics
- Creation of new or selection of availability set
- Selection of image from shared gallery