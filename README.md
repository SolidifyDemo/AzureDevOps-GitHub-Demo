# GitHub RoadShow, Azure DevOps and GitHub integrations #

[![Board Status](https://dev.azure.com/solidifydemo/0ea002ce-c62d-41f1-95fc-c1afff80c684/b784ad7c-2945-455d-821f-57f4d1152f5a/_apis/work/boardbadge/194f0f53-756a-4871-ad09-b43d0e302978)](https://dev.azure.com/solidifydemo/0ea002ce-c62d-41f1-95fc-c1afff80c684/_boards/board/t/b784ad7c-2945-455d-821f-57f4d1152f5a/Microsoft.RequirementCategory/)
[![Build Status](https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo/_apis/build/status/SolidifyDemo.AzureDevOps-GitHub-Demo?branchName=master)](https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo/_build/latest?definitionId=211&branchName=master)

## Details ##
Many of you have probably used Azure DevOps/TFS for years and have invested a lot of effort and time in it, maybe you are starting to use GitHub for some part of your development..
Azure DevOps and GitHub is a really good match and in this RoadShow event we are going to show you how the products integrate with each other.

We are going to show you things as:
- [Using Azure boards mentions in a GitHub Commit](https://docs.microsoft.com/en-us/azure/devops/boards/github/?view=azure-devops)
- [Azure boards and GitHub Commits and Pull Requests]()](https://docs.microsoft.com/en-us/azure/devops/boards/github/link-to-from-github?view=azure-devops)
- [Azure Pipelines with code in GitHub](https://docs.microsoft.com/en-us/azure/devops/pipelines/repos/github?view=azure-devops&tabs=yaml#access-to-github-repositories)
- [How to sync issues in GitHub with Azure Boards Work Items](https://github.com/marketplace/actions/github-issues-to-azure-devops)
- [How to use GritHub actions for other integrations](https://github.com/marketplace/actions/azure-devops-work-item-linker)

## What I did ##
- [Created project with Azure DevOps demo generator](https://azuredevopsdemogenerator.azurewebsites.net/)
  - https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo
- Created a repo in GitHub
  - https://github.com/SolidifyDemo/AzureDevOps-GitHub-Demo
- Cloned Azure DevOps repo to GitHub
Git Clone https://solidifydemo@dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo/_git/PartsUnlimited
```
Git remote remove origin
Git remote add origin https://github.com/SolidifyDemo/AzureDevOps-GitHub-Demo.git
Git branch -M master
Git push -u origin master
```
- Disabled Azure repos in Azure DevOps
- Set up oauth or PAT to connect to boards
- Setup up a build and connected to GitHub 
- Created branch policy in GitHub
- Added Sync GitHub Action to repo and configured it


## Links ##
- Migrating from TFVC to GitHub: https://solidify.dev/blog/migrating-from-tfvc-to-github
- Azure DevOps vs GitHub: what's the difference? https://solidify.dev/blog/azure-devops-vs-github-difference
- Meetup: https://www.meetup.com/swedish-ms-alm-devops/events/
- Solidify homepage: https://www.solidify.se/events
- Solidify on LinkedIn: https://www.linkedin.com/company/solidify-dev
- Recordings: https://www.youtube.com/channel/UChHumq_I3ne3nnoQ0B_KNgQ
- Demo repo in Azure DevOps: https://dev.azure.com/solidifydemo/Azure%20DevOps-GitHub%20Demo
