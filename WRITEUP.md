# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

Azure App service is more cost-effective than a VM becuase here I don't need to manage the operating system and server Infrastructure. It supports automatic scaling and built-in high availability whereas scaling a VM requires manual intervention. The deployment workflow of App Service is simpler, especially with GitHub Actions, making it easier to maintain and update the application where as deploying on a VM involves more operational overhead.

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the application later requires full control over the operating system, long-running background processes, deploying on a Virtual Machine would be more appropriate. Increased infrastructure customization needs could change the deployment decision.