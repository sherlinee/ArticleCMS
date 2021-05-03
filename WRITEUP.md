# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

## My preference for this project is an App service.
>A VM could also have been used my main need for Azure in this case was to use Azure as a platform to host to host the web app. I'm also avoiding extra costs and a VM is more expensive thus my preference for an App service. I'm less concerned about scalability in this case as the webapp doesn't expect a large number of users. I would have used a VM in the case of a large number of expected users or potential app growth so I wouldn't have to be worried about scaling. App service has the deployment center where I could be able to use my code from Github and link to deploy in Azure. Basically, an app service serves the current needs as I was more focused on app deployment rather than the os deployment stack but if I were to work on the app with the expectation of having more users, ensure more security, I would use a Virtual machine.

## App Service
###### Pros
- Support of multiple languages, such as Java, Node.js, PHP, and Python
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
