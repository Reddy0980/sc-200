## MetaData
Question Type : Single Choice

## Question
Contoso is a global manufacturing company with offices and factories in different parts of the world. They have been operating on an on-premises infrastructure for several years, but due to increased demand, they are moving some of their services and applications to the Azure Cloud. Contoso has several applications and services hosted on-premises, including Active Directory, Exchange, and SharePoint. They also have various web applications, databases, and APIs. The company's infrastructure includes virtual and physical servers, storage systems, and networking equipment. The on-premises infrastructure and applications are interconnected using a private network. The company also has a site-to-site VPN connection to Azure for some services.<br> <br>1. Planned Changes: Contoso plans to migrate some of its applications and services to Azure. They will also implement a hybrid cloud solution, where some services will continue to run on-premises while others will be moved to the Azure Cloud. The company also plans to implement a disaster recovery solution for its critical applications.<br><br>2. Technical Requirements: The company wants to ensure its applications and services are highly available, scalable, and secure. They want to implement a centralized logging solution to collect logs from their on-premises and Azure environments. They also want to create custom analytics rules in Azure Sentinel to detect and respond to security threats.<br><br>3. User Requirements: The users need to be able to access the applications and services regardless of where they are located. They want to use their existing Active Directory credentials to log into the Azure services.<br><br>4. Contoso has a requirement to monitor a critical web application hosted in Azure for any suspicious activity. Which of the following is the best approach to achieve this requirement? 

## Options
Option 1 : Use the built-in analytics rules in Azure Sentinel.
Option 2 : Create a custom analytics rule in Azure Sentinel. 
Option 3 : Use Azure Security Center to monitor the web application. 
Option 4 : Use Azure Network Watcher to monitor the web application. 

## Answers
Option 2 : 13

## Reference Links
https://docs.microsoft.com/en-us/azure/sentinel/detect-threats-custom 
 
## Explanation
The best approach to monitor a critical web application hosted in Azure for suspicious activity is to create a custom analytics rule in Azure Sentinel. By creating a custom analytics rule, Contoso can tailor the rule to meet their specific needs and ensure that it detects the suspicious activity they are concerned about. The built-in analytics rules in Azure Sentinel may not be sufficient to monitor a specific web application. Azure Security Center and Azure Network Watcher do not provide the same flexibility and customization as Azure Sentinel. 

## Products 


## Modules SubModules CTA 