## MetaData
Question Type : Single Choice

## Question
An external company has hired you as a security expert. You have noticed that a strange amount of data has been ingested via the AWS connector towards Micorosft Sentinel. To prevent further unwanted events, you want to disconnect Sentinel from AWS. What Azure CLI command can remove a data connector from Microsoft Sentinel? 

## Options
Option 1 : az sentinel connector delete --connector-id "ConnectorID" 
Option 2 : az sentinel data-connector delete --data-connector-id "ConnectorID" 
Option 3 : az sentinel delete data-connector --connector-id "ConnectorID" 
Option 4 : az sentinel delete connector --connector-id "ConnectorID" 

## Answers
Option 2 : 13

## Reference Links
 https://learn.microsoft.com/en-us/cli/azure/sentinel/data-connector?view=azure-cli-latest#az-sentinel-data-connector-delete
 
## Explanation
The correct Azure CLI command to remove a data connector from Microsoft Sentinel is (B) az sentinel data-connector delete --data-connector-id "ConnectorID". This command deletes the data connector with the specified ID. 

## Products 


## Modules SubModules CTA 