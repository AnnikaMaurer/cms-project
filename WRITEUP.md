# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
    - VM:
        - high costs
        - less scalable
        - good availability
        - more flexible
        - more time consuming for devs
    - App Service:
        - less costs
        - Auto-scaling
        - good availability
        - GitHub can be used
        - limited access
        - hardware limitations
- *Choose the appropriate solution (VM or App Service) for deploying the app*
    - Decision: App Service
- *Justify your choice*
    - For a project like that where the complexity of the App is already known and the development and debugging time should be very short, I think the App Service is the better choice. Moreover, I personally like GitHub

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 
If the app get bigger and more complex so that it reaches the limit of an App Service. If another languages is used that is not supported by App Service.