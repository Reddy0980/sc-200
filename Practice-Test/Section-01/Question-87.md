## MetaData
Question Type : Single Choice

## Question
Contoso is a global company that provides technology solutions for businesses. The company has a mix of Azure cloud and on-premises infrastructure, with multiple applications running across both environments.<br><br> 1. Contoso has multiple Azure services, including Virtual Machines, Azure SQL, Azure App Service, and Azure Active Directory. They also have on-premises infrastructure, including multiple servers running Microsoft Windows Server, Microsoft SQL Server, and Active Directory Domain Services. Applications running in the Azure environment include a custom web application hosted on Azure App Service and a customer relationship management (CRM) application that uses Azure SQL as its backend.<br> 2. Contoso's Azure environment is connected to its on-premises environment via a site-to-site VPN. Virtual Machines in Azure communicate with on-premises servers using a hybrid network configuration that includes a VPN Gateway and ExpressRoute. The CRM application on Azure SQL also communicates with an on-premises SQL server using the VPN.<br>  Planned Changes: Contoso plans to enhance its security posture by configuring Security Orchestration, Automation, and Response (SOAR) in Microsoft Sentinel. The company aims to automate incident handling and response, improve its security operations, and enhance their threat detection capabilities.<br> * Technical Requirements: Contoso needs to meet several technical requirements for the project, including:<br> * Creating automation rules to handle and respond to security incidents automatically.<br> * Developing custom playbooks to automate incident response processes.<br> * Bringing their machine-learning models to enhance the SOAR capabilities in Sentinel.<br> * Ensuring the security and compliance of the SOAR environment throughout the configuration process.<br> * User Requirements: Contoso's security analysts require the ability to automate incident handling and response to reduce the workload and improve efficiency. They also need to be able to customize incident response processes using playbooks. Additionally, the team wants to enhance their threat detection capabilities by bringing its machine-learning models to the SOAR environment.<br> * Contoso wants to develop a custom playbook to automate incident response processes in Microsoft Sentinel. Which feature in Sentinel should they use to create the playbook? 

## Options
Option 1 : Bring Your Own ML 
Option 2 : Automation Rules     
Option 3 : Workbooks 
Option 4 : Query Rules 

## Answers
Option 3 : 13

## Reference Links
https://learn.microsoft.com/en-us/azure/sentinel/automate-responses-with-playbooks#create-a-playbook-using-a-workbook

## Explanation
Workbooks in Microsoft Sentinel provide a customizable visual representation of data to enable security analysts to gain insights into the security environment. Workbooks can also be used to create custom playbooks to automate incident response processes. The custom playbook can be created by dragging and dropping widgets onto the workbook canvas and connecting them to form the desired process flow. 

## Products 


## Modules SubModules CTA 