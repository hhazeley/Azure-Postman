## Azure - Postman Project

### Description

This repository contains steps/information that can be used to connect [Postman][1] to an Azure environment so the environment can be managed using [Azure Rest API](https://docs.microsoft.com/en-us/rest/api/azure/) from [Postman][1].

### Steps


- Install [Postman][1] application
- Get information from Azure Environment
    - Tenant ID from Azure Active Directory 
    - Create or get application ID from an application within the tenant that has rights to subscription you plan to manage
    - Create an application key/secret 
    - Subscription ID
- From Postman, import [**Azure - Management Collection**](./Azure_Management.postman_collection.json) template
![Import Collection](https://i.imgur.com/xmS15W2.png "Import Collection")

    **You can load the [**Azure - Diagnostics Collection**](./Azure_Diagnostics.postman_collection.json) template if you are working on diagnostic scenario.**

- From Postman, import [**Azure Environment**](Azure.postman_environment.json) template
![Import Environment](https://i.imgur.com/NlrVozZ.png "Import Environment") 
+ Update **Postman** - **Azure Environment** with information from Azure Environment
![Update Environment details](https://i.imgur.com/iSNrbQ3.png "Update Environment details")



### Result

[Result 1](https://i.imgur.com/ZHmhNeC.png)

![Result 2](https://i.imgur.com/pgVpZpC.png)

[1]:https://www.getpostman.com/

### Video of Setup

[![YouTube Video](https://img.youtube.com/vi/2bfgeBKRxl4/0.jpg)](http://www.youtube.com/watch?v=2bfgeBKRxl4)

## Done!!