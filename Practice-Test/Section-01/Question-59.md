## MetaData
Question Type : Single Choice

## Question
You need to create a new Azure Sentinel workspace used by multiple departments within your organization. What is the recommended way to configure roles and permissions for this workspace?

## Options
Option 1 : Grant all users full access to the workspace 
Option 2 : Assign one user as the owner and have them manage all permissions 
Option 3 : Use Azure Lighthouse to manage roles and permissions across tenants 
Option 4 : Create a custom role to specify granular permissions for each department  

## Answers
Option 3:  13

## Reference Links
 https://learn.microsoft.com/en-us/training/modules/create-manage-azure-sentinel-workspaces/4-manage-workspaces-across-tenants-using-azure-lighthouse
 
## Explanation
 Using Azure Lighthouse allows you to manage roles and permissions across multiple tenants, making it the recommended option for managing roles and permissions for a workspace shared across multiple departments. Granting all users full access to the workspace (option a) is not recommended for security reasons. Assigning one user as the owner (option b) can lead to potential bottlenecks and delays in managing permissions. Creating a custom role (option d) may be an option but is not recommended in this scenario. 

## Products 


## Modules SubModules CTA 