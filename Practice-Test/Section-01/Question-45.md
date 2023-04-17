## MetaData
Question Type : Single Choice

## Question
A cybersecurity firm has hired you to help them with Microsoft Sentinel hunting. When hunting for threats in Microsoft Sentinel. How can you create a custom table to track specific security events in Microsoft Sentinel?

## Options
Option 1 : Use the built-in templates for security events
Option 2 : Add a new field to an existing table in Sentinel
Option 3 : Create a new query that extracts the necessary data and stores it in a custom table
Option 4 : Import a pre-made table from Azure Marketplace

## Answers
Option 3 : 12

## Reference Links
https://docs.microsoft.com/en-us/azure/sentinel/hunting#creating-a-custom-table

## Explanation
Though creating a new table in Sentinel is not an option, you can create a custom table by creating a new query that extracts the necessary data and stores it in a custom log table. This is a valuable technique for tracking a specific type of threat or event not included in Sentinel's built-in templates or standard tables. Options A and B are incorrect since the built-in templates do not allow for custom fields, and a new field added to an existing table would not constitute a new table entirely. Option D is also incorrect because importing a pre-made table from the Azure Marketplace would not allow for a customized table tailored to your needs.