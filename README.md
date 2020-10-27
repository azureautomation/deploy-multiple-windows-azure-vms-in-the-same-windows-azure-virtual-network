Deploy Multiple Windows Azure VMs in the Same Windows Azure Virtual Network
===========================================================================

            

[Windows Azure Scripting Center](http://www.windowsazure.com/en-us/documentation/scripts) |
[Get Started with Windows Azure PowerShell](http://go.microsoft.com/fwlink/?linkid=320929&clcid=0x409) |
[Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Description

Creates four Windows Server 2012 Virtual Machines across two separate cloud services and adds them to the same virtual network.


If the virtual network indicated does not exist then it is created. The user is prompted for administrator credentials which can be used to logon to the virtual machines.


This script will produce two cloud services, <ServiceNamePrefix>-1 and <ServiceNamePrefix>-2. Each cloud service will have two Virtual Machines, Host1 and Host2.

Example
 
Scenario
You need multiple Virtual Machines spread across separate cloud services in the same Virtual Network.
Requirements

  *  PowerShell Version 3.0 
  *  Windows Azure PowerShell 0.6.18 
See Also

  *  [Windows Azure Infrastructure Scripts](http://www.windowsazure.com/en-us/documentation/scripts/index/?solution=infrastructure&service=all)

Script Content

The content of the script is reproduced below

 

        
    
TechNet gallery is retiring! This script was migrated from TechNet script center to GitHub by Microsoft Azure Automation product group. All the Script Center fields like Rating, RatingCount and DownloadCount have been carried over to Github as-is for the migrated scripts only. Note : The Script Center fields will not be applicable for the new repositories created in Github & hence those fields will not show up for new Github repositories.
