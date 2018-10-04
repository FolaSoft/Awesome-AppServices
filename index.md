## What is a Web App on Azure?
Azure offers a product called Web Apps that lets any developer, on any platform quickly create web applications using a fully managed computing platform. Because it is fully managed by Microsoft Azure there is no need or requirement for patching, managing secuirty updates or other infrastructure oriented tasks.

Without the weight and toil of managing infrastructure the developer can focus on the app!

## What is App Service on Azure?
App Service is the managed computing platform that Azure Web Apps runs on! So Azure Web App is one type of "App" that runs on App Service. 

For example, there are API apps, Mobile Apps, Web Apps for Containers, Logic Apps, Azure Function Apps, Notification Apps and more.  

![App Service](/images/AppService.png)

These "Apps" all have one thing in common i.e. they all do some kind of "compute work" without the developer worring or managing infrastrucure. 

## What is the cost for Azure Web App?
May sound strange but Azure Web App is not priced directly! That is because Azure Web App is offered as a product (service) that is built on Azure App Service which has a cost association.

It may help to keep in mind that App Service on Azure (or Azure App Servicee is the 'platfomr' that offers other integrated services that becomes the 'product'. The that way, products are built on a platform and products inherit features from the its platform.
  
This is a fundamental distinction and it is why pricing is on the managed compute platform and not on the [Azure Web App](https://github.com/FolaSoft/Awesome-AppServices/blob/master/index.md#what-is-a-web-app-on-azure) which is a prodcut built on a managed computing [platform](https://github.com/FolaSoft/Awesome-AppServices/blob/master/index.md#what-is-app-service-on-azure).

What this means is that you can have a number of apps sharing the same App Service. The price of the App Service is defined in an App Service Plan which is the cost for a set of physical resources and capacity managed by Microsoft Azure. 

## What is an Azure App Service plan?
App Service Plan on Azure has a few distinct characteristics that describes the set of physical resources and capacity for the App Service.

These characteristic are  
- Region (West US, East US, North Europe etc)
- Operating System (Windows or Linux)
- SKU or Pricing tier (Free, Shared, Basic, Standard, Premium, Premium V2, and Isolated)
- Instance (small, medium, large)


After creating an App Service Plan, it is possible and reasonable (especially in Dev/Test scenarios) to share different apps on the same app service plan. Remmeber the cost is assocciated to the "plan" and not the "app". Many apps (including Azure Web Apps) can share the same app service plan.

## What is the price for App Service?

See Official pricing url https://azure.microsoft.com/en-us/pricing/calculator/ and click on App Service

![App Service Plan](/images/AppServicePricingCalculator.png)



## Is there a visual reference of App Service? 
<todo>

## Why are Azure names a tongue twister?
Yes it is true - Azure names can be a tongue twister.  

For example, Azure Web App is also referred to as Web App on Azure. 

Often times when the context is well known and the name gets longer or too concanated, the word "Azure" is dropped off and the most abbreviated form is used e.g. Azure App Service Plan becomes App Service Plan. 

## Where is the official azure documentation for Azure Web Apps? 
Visit https://aka.ms/az-appservice 
