# Notes #

## Azure Boards with GitHub commits and PR ##
- Open: https://dev.azure.com/solidifydemo and show the Kanban board
- Goto project settings and show GitHub connections
- Show ways to connect, oauth, PAT or username and password
- You can also connect from GitHub by adding Azure Boards to your repo from GitHub Marketplace
- Click overview and turn of Azure Repos

## Azure boards mentions in a GitHub Commit ##
- Goto GitHub: https://github.com/SolidifyDemo and add a status badge from Azure DevOps kanban settings in the ReadMe.md
```
[![Board Status](https://dev.azure.com/solidifydemo/0ea002ce-c62d-41f1-95fc-c1afff80c684/b784ad7c-2945-455d-821f-57f4d1152f5a/_apis/work/boardbadge/194f0f53-756a-4871-ad09-b43d0e302978)](https://dev.azure.com/solidifydemo/0ea002ce-c62d-41f1-95fc-c1afff80c684/_boards/board/t/b784ad7c-2945-455d-821f-57f4d1152f5a/Microsoft.RequirementCategory/)
```
- In the title or commit message write AB#20591
- Show branch policy that require pull request
- Do a change in the md and create a pull request, add fixed AB#20591 in the title or commit message

## Azure Pipelines with code in GitHub ##
- Turn of Branch policy
- Goto pipelines and create a new build, show classic and YAML
- Connect to the AzureDevOps-GitHub-Demo repo
- Select a dot net framework template
- Show assistant
- Save and build
- Go to recent build, select ... and copy the status badge and add to the MD file
```
[![Build Status](https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo/_apis/build/status/SolidifyDemo.AzureDevOps-GitHub-Demo?branchName=master)](https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo/_build/latest?definitionId=211&branchName=master)
```
- Commit: Fixes AB#20593

## How to sync issues in GitHub with Azure Boards Work Items ##
- Show this action at GitHub Marketplace: https://github.com/marketplace/actions/github-issues-to-azure-devops
- Show actions YAML
- Show secrets 
- Goto issues and add a new issue, add a picture
- Show that it turns up in Azure Boards. Close it

## How to use GitHub actions for other integrations ##
- Show this action: https://github.com/marketplace/actions/azure-devops-work-item-linker 
- Show code and parameters
- Do a small change and a PR
- Show that the link turn up in the Pull Request flow
