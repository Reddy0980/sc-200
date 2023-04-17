## MetaData
Question Type : Single Choice

## Question
XYZ Corp is a technology company that wants to connect its Azure assets to Microsoft Defender for Cloud. Which Azure CLI commands can be used to install the Log Analytics agent on their virtual machines manually?

## Options
Option 1 : az vm extension set
Option 2 : az policy assignment create
Option 3 : az security assessment-metadata show
Option 4 : az ad app show

## Answers
Option 1 : 12

## Reference Links
https://docs.microsoft.com/en-us/azure/azure-monitor/agents/log-analytics-agent#manual-installation<br>
https://learn.microsoft.com/en-us/cli/azure/vm/extension?view=azure-cli-latest

## Explanation
The Azure CLI command az vm extension set can be used to manually install the Log Analytics agent on virtual machines. This command enables you to add an extension to an Azure virtual machine that runs the Log Analytics agent. The extension can be added using a specific configuration file with the workspace ID and key. Options B, C, and D are unrelated to manually installing the Log Analytics agent on virtual machines.

## Products 
Azure Active Directory 

## Modules SubModules CTA  
Deploy and manage identity infrastructure:Implement hybrid identity with Windows Server:learn.microsoft.com/en-us/azure/active-directory/hybrid/
