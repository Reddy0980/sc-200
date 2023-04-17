## MetaData
Question Type : Single Choice

## Question
Contoso is a global company that provides technology solutions for businesses. The company has a mix of Azure cloud and on-premises infrastructure, with multiple applications running across both environments.<br>Contoso has multiple Azure services, including Virtual Machines, Azure SQL, Azure App Service, and Azure Active Directory. They also have on-premises infrastructure, including servers running Microsoft Windows Server, Microsoft SQL Server, and Active Directory Domain Services. Applications running in the Azure environment include a custom web application hosted on Azure App Service and a customer relationship management (CRM) application that uses Azure SQL as its backend.<br>Contoso's Azure environment is connected to its on-premises environment via a site-to-site VPN. Virtual Machines in Azure communicate with on-premises servers using a hybrid network configuration that includes a VPN Gateway and ExpressRoute. The CRM application on Azure SQL also communicates with an on-premises SQL server using the VPN.<br><br>1. Planned Changes: Contoso plans to implement a new data classification and normalization process using Microsoft Sentinel. The company aims to improve its security posture by identifying sensitive data in its environment and standardizing the data format to enable better analysis.  <br>2. Technical Requirements: Contoso needs to meet several technical requirements for the project, including: <br>Implementing data classification policies to identify sensitive data in their Azure and on-premises environments. <br>Normalizing the format of data from different sources using parsers. <br>Storing normalized data in a central location for analysis. <br>Ensuring security and compliance of the data throughout the normalization process. <br>3. User Requirements: Contoso's users require the ability to access and analyze the normalized data from multiple sources, including Azure and on-premises environments. They also should be able to monitor the data for security and compliance issues.<br><br>What is the purpose of parsers in the data normalization process? 

## Options
Option 1 : To identify sensitive data in the environment. 
Option 2 : To standardize the format of data from different sources. 
Option 3 : To store normalized data in a central location for analysis.
Option 4 : To monitor the data for security and compliance issues.

## Answers
Option 2 : 13

## Reference Links
https://learn.microsoft.com/en-gb/azure/sentinel/normalization-about-parsers 

## Explanation
Parsers are used to standardize data format from different sources to enable better analysis. Microsoft Sentinel includes built-in parsers that can be used out-of-the-box, or custom parsers can be created to meet specific requirements. Parsers are essential for the data normalization process, enabling Sentinel to understand and analyze the data. 

## Products 


## Modules SubModules CTA 