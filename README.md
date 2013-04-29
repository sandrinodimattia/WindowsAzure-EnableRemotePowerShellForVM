# Enable-RemotePowerShellForVM

A script which automates the tasks you need to execute on your local machine in order to use Remote PowerShell to a Windows Azure Virtual Machine:

 - Parse a publish settings file to get the management certificate and the subscription ID
 - Find the public port for Remote PowerShell of a specific Virtual Machine
 - Download the certificate used by the Virtual Machine for Remote PowerShell
 - Install this certificate in the trusted root store
 - Give me some examples of how I could use Remote PowerShell for that machine
 
More Information: [Automatically configuring Remote PowerShell for Windows Azure Virtual Machines on your machine](http://fabriccontroller.net/blog/posts/automatically-configuring-remote-powershell-for-windows-azure-virtual-machines-on-your-machine/)