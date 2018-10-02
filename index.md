## What is a Web App on Azure?
Azure offers a product called Web Apps that lets any developer, on any platform quickly create web applications using a fully managed computing platform. Because it is fully managed by Microsoft Azure there is no need or requirement for patching, managing secuirty updates or other infrastructure oriented tasks.

Without the weight and toil of managing infrastructure the developer can focus on the app!

## What is App Service on Azure?
App Service is the managed computing platform that Azure Web Apps runs on! So Azure Web App is one type of "App" that runs on App Service. For example, there are API apps, Mobile Apps, Web Apps for Containers, Logic Apps, Azure Function Apps, Notification Apps and more.  These "Apps" all have one thing in common i.e. they all do some kind of "compute work" without the developer worring or managing infrastrucure. 

## What does pricing of Azure Web App look like?

So far App Service has being introduced as an 'abstract thing' that other more 'concrete things' are built on top off.  
There is a fundamental distinction because pricing is on the managed compute platform (remember that 'abstract thing') and not on the concrete thing like the Azure Web App.

What this means is that you can have a number of apps in an App Service plan which is the cost for a set of physical resources and capacity managed by Microsoft Azure. 

## What makes up an Azure App Service plan?
App Service Plan on Azure has a few distinct characteristics that describes the set of physical resources and capacity for the App Service.

These characteristic are  
- Location (West US, East US, North Europe etc)
- SKU or Pricing tier (Free, Shared, Basic, Standard, Premium, Premium V2, and Isolated
- Operating System (Windows or Linux)

After creating an App Service Plan, it is possible and reasonable (especially in Dev/Test scenarios) to share different apps on the same app service plan. Remmeber the cost is assocciated to the "plan" and not the "app".

## Is there a visual reference of App Service? 

## Why are Azure names a tongue twister?
Yes it is true - Azure names can be a tongue twister.  For example, Azure Web App is also referred to as Web App on Azure. Often times when the context is well known and the name gets longer or concanated, the word "Azure" is dropped off and the most abbreviated form is used e.g. Azure App Service Plan becomes App Service Plan. 

## Where is the official azure documentation for Azure Web Apps? 
Visit https://aka.ms/az-appservice 
