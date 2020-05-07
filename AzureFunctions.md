## What is azure function.
    Azure function is `Serverless` platform
    Azure function = `Event` + `Code`
    User platform as a Service wherever possible. [e.g. CosmosDb, Autho0 ]
    Run your custom code on Azure function.
    1. Responds to events
    2. Function as a Service
## Example of trigger events for Azure function
- *Time* : Run a regular task on Regular Schedule. i.e. nightly batch job
- *Data* : Triggers a function on data change. i.e. Notification message or file uploaded to blob storage
- *Web*  : Triggers a function on respond to Http request or web hook
## What services Azure virtual machine does provide.
+ Install whatever you want
    - Web server, Windows service etc
+ Infrastructure as a Service (IaaS)
    - Complete control over server
    - Choose your operating system
+ You are responsible for Resource management
    - Patching and Maitaining
    - Scalling
+ Operational Overhead
## Azure App Service
+ Platform as a Service (PaaS)
    - Azure provide all service till Operating System level Plateform
+ Azure Web Application
    - Easy to Deploy
    - Choice of many framework
+ Hosted in `Hosting plan`
    - Combine multiple site on single server
    - scale up to many server
+ Web Jobs
    - Simplified background task.
    - Basis for Azure function.
# Best practices to reduct cost while using Azure Function
+ Reduce cost with
    - Faster invocation time
    - Fewer Invocation
    - Reduce memory requirement
+ Consomption paln
    - Limited to file minutes per execution
    - Optional Daily Quota
## Play aroung with Azure function without Azure account
1. Go to wwww.tryfunctions.com/try
> Azure functions are created on top of the Azure web apps hence all the features available in Azure Web App are available in Azure function.
## Types of Triggers
- Timers
- Http Requests
- Queue Messages 
- Blobs
- Cosmos DB

    

