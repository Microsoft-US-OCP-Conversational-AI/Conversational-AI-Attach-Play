# What The Hack - Conversational-AI-Attach-Play

## Introduction
Microsoft Bot services provided easy to build code free solutions for citizen developers to build a bot that can naturally interact with users by easily integrating Cognitive services and other Microsoft products like Teams, Azure Communication Services. The goal of this hack is to build out a demo of a Financial Services Bot which focuses on ESG.

## Learning Objectives

This Conversational AI Attach Play hack will help you to learn:
1. How to use QNA maker to create multi-turn knowledge base
1. How to use Bot Framework Composer to build a code free Bot
1. Understand the Azure AI services within Bot Solution (LUIS, Direct Line Speech)
1. Publish your BOT into Azure and Embedded into our sample web Application 
1. Integrate your BOT into Microsoft Teams which enables human interactions Teams Channel
1. Integrate your BOT with Azure Communication Services which enables human interactions via phone, videos, and SMS
1. Implement DevOps pipeline best practices
1. Extend the bot with Azure Data Services to enable advanced ML and big data capabilities. (Optional)

## Challenges
 - [Challenge 0](./Student/Challenge0.md) - Setup and Introduction
 - [Challenge 1](./Student/Challenge1.md) - Create Multi-Turn QNA Knowledge Base
 - [Challenge 2](./Student/Challenge2.md) - Create LUIS Intent
 - [Challenge 3](./Student/Challenge3.md) - Make API Call  
 - [Challenge 4](./Student/Challenge4.md) - publish your bot to Azure and enable Teams Channel
 - [Challenge 5](./Student/Challenge5.md) - Embed your Bot to the sample Front End Web Application and enable Direct Line Speech (In progress)
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