# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

## My preference for this project is an App service.
> A VM could also have been used but my main need for Azure in this case was to use Azure as a platform to host the web app. Basically, an app service serves the current needs as I was more focused on app deployment rather than the os deployment stack but if I were to work on the app with the expectation of having a large number of users, I would use a Virtual machine to ensure a higher scaling processing power and I'd want full control to enable more security. I'm also avoiding extra costs and a VM is more expensive thus my preference for an App service. App service has the deployment center where I could be able to use my code from Github and link to deploy in Azure. I did it in less time than I would have by starting to set up a VM.

## App Service
###### Pros
- Support of multiple languages, such as Java, and Python
- Cloud provider manages infrastructure so eases the developer's work
- High availability and scalability
- Continuous deployment using GitHub or any Git repo.
###### Cons
- Limited access control
- Pay for the service plan even when the web app is not running

 ## Virtual Machine
###### Pros
- Full control of infrastructure
- High availability and scalability
###### Cons
- More expensive than App service
- More time consuming and complex to host webapps
