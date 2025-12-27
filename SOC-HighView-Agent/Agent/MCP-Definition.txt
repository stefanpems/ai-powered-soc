#Reference:
https://learn.microsoft.com/en-us/azure/sentinel/datalake/sentinel-mcp-use-tool-copilot-studio#add-a-custom-tool-collection

#Server name:
SOC-HighView-MCP

#Server description:
Set of tools that allow retrieving high-level statistical insights about SOC operations by extracting them from Microsoft Sentinel.

#Server URL:
https://sentinel.microsoft.com/mcp/custom/<Toolset-Collection-Name-In-Defender>
(This URL can be retrieved from Advanced Hunting in Defender)

#Authentication:
OAuth 2.0

#Type:
Manual

#Client ID:
(Read it from the App Registration)

#Client Secret:
(Create and store it from the App Registration)

#Authorization URL:
https://login.microsoftonline.com/<tenant ID>/oauth2/v2.0/authorize
(take the tenant ID from the App Registration)

#Token URL template:
https://login.microsoftonline.com/<tenant ID>/oauth2/v2.0/token
(take the tenant ID from the App Registration)

#Refresh URL:
https://login.microsoftonline.com/<tenant ID>/oauth2/v2.0/token
(take the tenant ID from the App Registration)

#Scope: 
4500ebfb-89b6-4b14-a480-7f749797bfcd/.default
