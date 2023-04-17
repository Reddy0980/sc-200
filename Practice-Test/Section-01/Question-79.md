## MetaData
Question Type : Single Choice

## Question
Contoso Corporation is a global company with operations in various industries. The company's IT infrastructure consists of both Azure Cloud and On-Premises resources. The company uses Microsoft Sentinel as its cloud-native security information and event management system. The company has implemented data classification and normalization to manage its security operations better.<br>Contoso's infrastructure consists of various Azure services, such as Azure Virtual Machines, Azure App Service, Azure SQL Database, Azure Active Directory, and On-Premises Active Directory. The company also uses various third-party applications and tools to manage its infrastructure.<br>The company's infrastructure and data flow between services and applications are interconnected. For example, Contoso's web application on Azure App Service communicates with Azure SQL Database for database operations. Active Directory is used to manage user authentication and authorization for various applications.<br><br>1. Planned Changes: Contoso plans to implement a new data processing system requiring new data classification and normalization rules are created in Microsoft Sentinel. The system will process sensitive data; the rules must be accurate to ensure proper data handling.<br><br>2. Technical Requirements: The company must ensure that data classification and normalization rules are accurate and up-to-date to comply with industry regulations. The system must detect and normalize data from various sources, including custom applications, and support different data formats.<br><br>3. User Requirements: Contoso's security team requires an easy-to-use system for managing data classification and normalization rules. The system should be able to parse data from different sources and normalize them according to the rules. Contoso plans to implement a new data processing system that requires classification and normalization. Which options would be the best solution for implementing data classification and normalization in Microsoft Sentinel? 

## Options
Option 1 : Use a built-in ASIM parser to parse data and create normalization rules. 
Option 2 : Create custom parsers for each data source and use them to create normalization rules.
Option 3 : Use Azure Cognitive Services to create normalization rules. 
Option 4 : Use a third-party tool to create normalization rules.

## Answers
Option 2 : 13

## Reference Links
https://learn.microsoft.com/en-gb/azure/sentinel/normalization-about-parsers 

## Explanation
Creating custom parsers for each data source provides the most accurate and customizable solution for classification and normalization. This approach allows fine-tuning the normalization rules to accurately reflect the data's meaning. 

## Products 


## Modules SubModules CTA 