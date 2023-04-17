## MetaData
Question Type : Single Choice

## Question
Contoso is a financial services company; they have received a security alert in Microsoft Defender for Cloud indicating potential malware activity in their Azure resources. The security team wants to remediate the alert by taking immediate action. Which Azure CLI command should they use to isolate a virtual machine as part of the remediation process? 

## Options
Option 1 : az network nsg rule create
Option 2 : az vm deallocate 
Option 3 : az network nic ip-config update 
Option 4 : az vm update

## Answers
Option 2 : 12

## Reference Links
https://docs.microsoft.com/en-us/cli/azure/vm?view=azure-cli-latest#az-vm-deallocate

## Explanation
To isolate a virtual machine as part of the remediation process, the security team should use the Azure CLI command "az vm deallocate". This command stops a virtual machine and deallocates resources. This will isolate the virtual machine and prevent further malware activity.

## Products 


## Modules SubModules CTA 