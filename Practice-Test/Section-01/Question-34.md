## MetaData
Question Type : Single Choice

## Question
You have a mixed environment consisting of both Azure and non-Azure resources. You want to connect your non-Azure resources to Microsoft Defender for Cloud to ensure their security. Which of the following statements about connecting non-Azure resources to Microsoft Defender for Cloud is true?
 
## Options
Option 1 : Connecting AWS and GCP accounts to Microsoft Defender for Cloud is possible.
Option 2 : Non-Azure resources can only be connected to Microsoft Defender for Cloud if running on a Windows operating system.
Option 3 : To connect your non-Azure resources to Microsoft Defender for Cloud, deploy a Microsoft monitoring agent on the target machine.
Option 4 : Non-Azure resources can be connected to Microsoft Defender for Cloud without additional configuration.

## Answers
Option 3 : 12

## Reference Links
https://learn.microsoft.com/en-us/training/modules/connect-non-azure-machines-to-azure-defender/3-connect-non-azure-machines

## Explanation
To connect non-Azure resources to Microsoft Defender for Cloud, you must deploy a Microsoft monitoring agent on the target machine. This agent collects data from your non-Azure resources and sends it to Microsoft Defender for Cloud for analysis. This can be done on non-Azure machines running Windows or Linux. Options A and B are incorrect as other non-Azure resources can be connected besides AWS and GCP, and non-Windows machines can also be connected. Option D is incorrect as the additional configuration is required to connect non-Azure resources to Microsoft Defender for Cloud.

## Products 
Azure Policy

## Modules SubModules CTA
Deploy and manage identity infrastructure:Implement Group Policy Objects:learn.microsoft.com/en-us/windows/security/threat-protection/windows-firewall/
