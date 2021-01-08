# What The Hack - Conversational-AI-Attach-Play

## Introduction
The Conversational AI Attatch Play WhatTheHack will take you through architecting a Chatbot with an FSI industry focus that is more intelligent that an out of the box chatbot. This is a challenge-based hack. It's NOT step-by-step. Don't worry, you will do great whatever your level of experience! You will be guided through different tasks to implement the FSI ChatBot by leveraging a serverless architecture within Azure using a combination of Azure Bot Composer, QnA Maker, LUIS, Azure Databricks, and Azure Communication Services. The focus is on building ontop of what you know from Azure Bot Services and attaching further services to enable a truely Enterprise scale bot.  The intent is to have you practice the tools, technologies and services our partners are asking you about. Let's try to go out of your comfort zone, try and learn something new. And let's have fun! And don't forget there are proctors around you, just raise your hand at any time!


## Learning Objectives

This Conversational AI Attach Play hack will help you to learn:
1. How to use QNA maker to create multi-turn knowledge base
1. How to use Bot Framework Composer to build a code free Bot
1. Understand the Azure AI services within Bot Solution (LUIS, Direct Line Speech)
1. Publish your Bot into Azure and Embedded into our sample web Application 
1. Integrate your Bot into Microsoft Teams which enables human interactions Teams Channel
1. Integrate your Bot with Azure Communication Services which enables human interactions via phone, videos, and SMS
1. Implement DevOps best practices
1. Extend the bot with Azure Data Services to enable advanced ML and big data capabilities. (Optional)

## Challenges
 - [Challenge 0](./Student/Challenge0-Setup.md) - Setup and Introduction
 - [Challenge 1](./Student/Challenge1-QnA.md) - Create Multi-Turn QNA Knowledge Base
 - [Challenge 2](./Student/Challenge2-LUIS.md) - Create LUIS Intent
 - [Challenge 3](./Student/Challenge3-API.md) - Make API Call  
 - [Challenge 4](./Student/Challenge4-Deployment.md) - Publish your Bot to Azure and enable Teams Channel
 - [Challenge 5](./Student/Challenge5-FrontEnd.md) - Embed your Bot to the sample Front End Web Application and enable Direct Line Speech (In progress)
 - [Challenge 6](./Student/Challenge6.md) - Integrate your Bot with Azure Communication Services (In progress)
 - [Challenge 7](./Student/Challenge7.md) - Implement DevOps best practices into your Bot (In progress)
 - [Challenge 8](./Student/Challenge8.md) - Add Advanced intelligence to your Bot using Azure Data Services (In progress)

## Prerequisites
- Your own Azure subscription with **owner** access. See considerations below for additional guidance.
- [Visual Studio Code](https://code.visualstudio.com)
- [Git SCM](https://git-scm.com/download)

## Repository Contents (Optional)
- `../Student`
  - Student Challenge Guides
- `../Student/Resources`
  - Student's resource files, code, and templates to aid with challenges

## Considerations

If you are running this hack with a group, here are some options for providing access to Azure:
- Each person/team uses their own subscription (ideal)
- Use a single subscription with each person/team using a different resource group
- Use a single subscription and resource group, with each person/team creating resources within the single resource group (less ideal)

Regardless of the option you choose, you'll have to consider:
- [Azure default quotas and resource limits](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits) (for example, # of VMs allowed per region or subscription)
- Unique naming of resources - many services may require a globally unique name, for example, App service, container registry.

## Contributors
Annie Xu;
Anthony Franklin;
Ariel Luna;
Claire Rehfuss;
Praveen Rawat;
Sowmyan Soman Chullikkattil;
Wayne Smith.
