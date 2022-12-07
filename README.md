# powershell_commands
Useful PowerShell commands


### Installing ADDS and Promoting the server to a DC

Install-WindowsFeature -name AD-Domain-Services -IncludeMangementTools   
Install-ADDSForest -DomainName <DOMAIN NAME> -InstallDNS
