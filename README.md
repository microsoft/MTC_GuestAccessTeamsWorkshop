# Workshop - Automating Secure Collaboration in Microsoft Teams
Secure collaboration in Microsoft Teams comes to the forefront even more when you add Guests into the mix. Automating this process becomes very important because doing so manually doesn't scale. This workshop takes you through the process of setting up, creating/developing, and provisioning the assets to create individual Microsoft Teams with Guest Access on or off on a per-team basis.

This workshop leverages the following services:
* Azure Active Directory Application Registrations
* SharePoint Online
* Power Automate
* Microsoft Graph
* Power Apps
* Microsoft Teams

At the end of this workshop you will have a working proof-of-concept application that allows you to submit a request for a Microsoft Team that follows a provisioning workflow with Guest Access on or off on a per-team basis.

## Setup
This repo is organized into a few folders
* [00-Setup](https://github.com/microsoft/MTC_GuestAccessTeamsWorkshop/tree/main/00-Setup): Folder containing setup documentation for this workshop
* [01-AAD App Registration](./01-AAD App Registration): Folder containing lab documentation for Module 1 to create an Azure Active Directory Application Registration
* [02-SharePoint TeamRequests List](): Folder containing lab documentation for Module 2 to set up the SharePoint Online list to hold out Team requests
* [03-Power Automate and Microsoft Graph](): Folder containing lab documentation for Module 3 to create a Flow to conduct our workflow/business logic when a request for a Team is submitted (added to the SharePoint list)
* [04-Power Apps](): Folder containing lab documentation for Module 4 to create a Power App that will be the entry point to request a Team. This will be exposed as an app in Microsoft Teams

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
