# Notes #

## Azure Boards with GitHub commits and PR ##
- Open: https://dev.azure.com/solidifydemo
- Goto project settings and show GitHub connections
- Show ways to connect, oauth, PAT or username and password
- You can also connect from GitHub by adding Azure Boards to your repo from GitHub Marketplace
- Click overview and turn of Azure Repos

## Azure boards mentions in a GitHub Commit ##
- Goto GitHub: https://github.com/SolidifyDemo and att a status badge from Azure DevOps kanban settings
- In the title or commit message write AB#id
- Create a branch policy and require pull request
- Do a change in the md and create a pull request, add fixed AB#id in the title or commit message

## Azure Pipelines with code in GitHub ##
- Turn of Branch policy
- Goto pipelines and create a new build, show classic and YAML
- Connect to the AzureDevOps-GitHub-Demo repo
- Select a dot net framework template
- Show assistant
- Save and build
- Go to recent build, select ... and copy the status badge and add to the MD file

## How to sync issues in GitHub with Azure Boards Work Items ##
- Show this action at GitHub Marketplace: https://github.com/marketplace/actions/github-issues-to-azure-devops
- Show secrets and parameters in Actions YAML
- Goto issues and add a new issue
- Show that it turns up in Azure Boards

## How to use GitHub actions for other integrations ##
- Show this action: https://github.com/marketplace/actions/azure-devops-work-item-linker 
- Show code and parameters
- To a small change
