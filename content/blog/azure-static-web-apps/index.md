---
title: Azure Static Web Apps
date: "2021-08-16T22:12:03.284Z"
description: "A light-weight Azure web app service with built-in automated CICD through Github Actions."
---

![Static Web App Overview](./azure-static-web-apps-overview.png)

[Azure Static Web Apps](https://docs.microsoft.com/en-us/azure/static-web-apps/overview) provide a streamlined way to deploy a modern website. 

Disclaimer: This blog is actually hosted as a Static Web App. 

**They're low cost:** Static Web Apps can reduce the total cost of ownership for a website. The free tier is great for personal projects and hosting a development website. The Standard tier is only $9/month and comes with 99.5% availability. 

**Free SSL Certificate:** Static Webs Apps come with a free SSL certificate! You can use it for up to 2 custom domains with free tier and up to 5 custom domains with standard.

**Easily automated CICD:** If you are building an application with a modern SPA framework (such as React, Gatsby, or Vue, plus a few others), when you create your Static Web App resource, you are able to able to point it at a Github repository. After choosing your repository, you can then select the type of framework that you're using and Azure will take care of generating `YAML` to build and release your application with [Github Actions](https://github.com/features/actions). 

**Built-in Azure Functions**: If your website requires a layer of APIs, Static Web Apps also account for those. The resource comes with built in [Azure Functions](https://docs.microsoft.com/en-us/azure/static-web-apps/add-api?tabs=vanilla-javascript), that will deploy directly to the Static Web App based on what is inside of your `api` folder. 

If you're looking for a quick and easy way to deploy an application, I recommend taking a look at Azure Static Web Apps. They're quick, fun, and take most of the stress out of deployment! 

[QuickStart Documentation](https://docs.microsoft.com/en-us/azure/static-web-apps/getting-started?tabs=react)



