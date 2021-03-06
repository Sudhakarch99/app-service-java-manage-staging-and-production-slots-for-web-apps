---
services: Appservice
platforms: java
author: jianghaolu
---

## Getting Started with Appservice - Manage Web App Slots - in Java ##


  Azure App Service basic sample for managing web apps.
   - Create 3 web apps in 3 different regions
   - Deploy to all 3 web apps
   - For each of the web apps, create a staging slot
   - For each of the web apps, deploy to staging slot
   - For each of the web apps, auto-swap to production slot is triggered
   - For each of the web apps, swap back (something goes wrong)
 

## Running this Sample ##

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-sdk-for-java/blob/master/AUTH.md).

    git clone https://github.com/Azure-Samples/app-service-java-manage-staging-and-production-slots-for-web-apps.git

    cd app-service-java-manage-staging-and-production-slots-for-web-apps

    mvn clean compile exec:java

## More information ##

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212)

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.