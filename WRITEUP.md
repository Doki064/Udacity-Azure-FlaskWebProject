# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

#### Cost

When deploying the CMS app, App Service is a more cost-effective option than VM. Additionally, you can lower costs for development and production by selecting Free services during testing.

#### Scalability

Both VM and App Service are scalable options. VMs can be scaled by increasing the number of VMs, while App Service can be scaled horizontally and vertically. Both options are easy to set up for scalability. However, App Service is quicker to scale than VM.

#### Availability

Both of VM and App Service have high availability.

#### Workflow

If you have a simple app, App Service is the best choice because it’s easy to set up for continuous deployment using Github, Azure DevOps, and other tools. In contrast, VMs require more complex steps before your app is online. For example, you need to set up the tools you need to run your code. App Service already provides you with the necessary tools.

#### Solution/Choice for current CMS App

App Service is the best option for this CMS app because the code or app doesn’t require specific functionality that needs to be customized. Mostly, we do simple CRUD, so there’s no need for high processing.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

If this CMS becomes more popular, it could become more expensive due to requiring more hardware/compute power. Then we need to move the deployment to VM option.
