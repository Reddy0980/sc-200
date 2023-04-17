## MetaData
Question Type : Single Choice

## Question
A security analyst at a financial institution wants to create a custom analytics rule in Microsoft Sentinel to detect any attempts to exfiltrate sensitive data through email. Which data sources can the analyst use to create this rule?

## Options
Option 1 : Azure Active Directory 
Option 2 : Azure Sentinel security events 
Option 3 : Microsoft 365 security events
Option 4 : Azure Virtual Network logs 
 
## Answers
Option 3 : 13

## Reference Links
https://learn.microsoft.com/en-us/azure/sentinel/detect-threats-custom#using-advanced-hunting-to-create-custom-detection-rules
  
## Explanation
To detect attempts to exfiltrate sensitive data through email, the security analyst should use Microsoft 365 security events as the data source for the custom analytics rule. These events include email activities, such as sending and receiving emails, which can be used to identify suspicious behavior. Azure Active Directory provides information about users and their access to resources but does not provide information about email activities. Azure Sentinel security events and Azure Virtual Network logs may contain information relevant to security monitoring, but they are not explicitly designed for email monitoring. 

## Products 


## Modules SubModules CTA 