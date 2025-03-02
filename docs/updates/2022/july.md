---
title: July Updates
sidebar_label: July Updates
---


## 1. Studio

#### Restructured Studio navigation as per the usage flow

  

All options in the Studio navigation are reordered according to the usage flow. This makes more convenient for you to navigate between the options sequentially when configuring a bot.

  
New structure of the options in Studio's left navigation bar -

  

![](https://i.imgur.com/02x4CVF.png)

  

Once you enter a particular screen (say Train), here is how the sub-options are rearranged-

  

![](https://i.imgur.com/hgkY4sq.png)

  
  

#### Autocomplete suggestions for bot users

  

You can now make your bot users' life easy through our autocomplete suggestions. With this feature, the bot can predict the rest of the word when users types in the bot.

  

Scope of the Autocomplete feature -

  

1.  **Prompt level**- This works inside a prompt (after you ask a question and wait). You can configure this for **Database Column**, **List entity**, and **User properties**.

2.  **Global level** - This works outside of a Journey improving discoverability.

> [Know more](https://docs.yellow.ai/docs/platform_concepts/studio/build/nodes/prompt-nodes/#auto-complete)

  
  
  

#### Zero Shot Model to replace manual training of intents

Now our system can automatically identify intents based on the intent naming. It works on Zero Shot Learning where you do not need to manually train each utterance. Just name intents properly to make it work best globally. For complete guidelines, see [Naming intents](https://docs.yellow.ai/docs/platform_concepts/studio/train/intents/#4-best-practices).

  
  
  

#### Make Localisation more effective in Nodes

  

We do have auto-translation support that can translate your text to your preferred language. However, there are several cases where your tranlation quality is compromised. With this release, you can get your text translated properly and add translated content for each node manually.

> [Know more](https://docs.yellow.ai/docs/platform_concepts/studio/build/localization)

  

#### Real-time Conversation Logs

You can now monitor all the conversations real-time. The auto-tagging of problems identified in the conversation are also made real-time.

  

> [Know about Conversation logs](https://docs.yellow.ai/docs/platform_concepts/studio/analyze/chat-logs)

  
  

#### Add API to Sync data to the database

  

The **Sync database** node is available in Workflow - actions. You can now insert, update or import databases to external sources using APIs. You can update database tables in a scheduled manner using APIs.

* **Export file format**:  CSV

  

> [Know more](https://docs.yellow.ai/docs/platform_concepts/studio/build/nodes/action-nodes#sync-database)

  

#### Quick Reply buttons in WhatsApp

Earlier, WhatsApp bots used to support only lists for Quick replies. With this release, Quick replies node can also have buttons. You can switch between buttons and numbered list according to your preference.

It supports upto three buttons and each button can have up to 20 characters. If you try to add more than 3 buttons, it defaults to the numbered list.

  
  

> [Know more](http://localhost:3000/docs/platform_concepts/studio/build/nodes/prompt-nodes#quick-reply-node-for-whatsapp)

  

#### New languages support in Document Cognition

  

Document Cognition now supports five more European languages. You can input content in Czech, Romanian, Polish, Croatian, Slovakia) German, Spanish, and French.

  


>  [Know about Document cognition](https://docs.yellow.ai/docs/platform_concepts/studio/train/what-is-document-cognition)

## 2. Inbox 

#### The search functionality of Chat is revamped 

Agents can find information like details & messages from all their chat tickets easily.

![](https://i.imgur.com/Kn0ajbu.png)


#### Data Explorer Integration was added to Inbox

Inbox data is exposed to Data explorer which allows businesses to build, and monitors custom reports & dashboards of choice.

**![](https://lh6.googleusercontent.com/YHOhZs9sJtFTkeRp_Fmtu7gOTMMUB7HJiTHmhY2AUoQWB844DUZlEe7sBFRjZCQTy0r2LPofIxSWeThywXJiw4c-9NdJR7ekKUKY_gi7x6Gh25xz7hgrnvdqfnMMeid7jSd6vEIKd_bct4v16N2WVOdDNg)**

#### The video calling option is enhanced

Customers can set custom virtual backgrounds for their agents and also redirect end-users to their own websites after the video call -to provide a consistent support experience. 

> [Know more](https://docs.yellow.ai/docs/platform_concepts/inbox/inbox-settings/chats-configuration/video-call-settings)

#### Email ticketing now works without any code

No-code email ticketing is added to support the use case in cloud bots. 

> Know [more](https://docs.yellow.ai/docs/platform_concepts/inbox/email-ticketing).




##### Detailed Agent performance reports can be downloaded for email tickets

A detailed dump of all metrics related to agents resolving tickets, to better understand the efficiency & performance of the team. 

> Know [more](https://docs.yellow.ai/docs/platform_concepts/inbox/reports/ticket-agent-performance-report). 


##### Analytics are displayed for Email ticketing 

Agents & Admins can get a quick insight into the status of incoming tickets, and performance metrics like AHT, FRT etc., to make decisions to optimize them.

![](https://i.imgur.com/e896xIT.png)


##### Email ticketing transcripts can be copied and downloaded

Transcripts for each email ticket are used for legal, quality assurance or for auditing purposes. They can now be copied and downloaded. 

**![](https://lh4.googleusercontent.com/8vaNdIlLcn4GwIRHGQ2UPXXZGevq6fwVi9G_WLjCvwzoREH1ZSHi_O14ut-p9OZi27dKwAqLSkGnDs0e-1pTV7leB5CfIFlSu6hv0RrmvBXPhNQGxajZ_Md-_aGdg7mf2kE1Qaf1Ghz6O0G5n8pMXSryfQ)**

#### Email IDs can be categorised based on groups 

You can now map email IDs to certain groups to categorize & respond back easily.

**![](https://lh6.googleusercontent.com/e8UgQ44qFMHGmsk9nSZ6b1gZIbcgtsSrh9eeTBJ7pLhLkydsaKmmGwoG3QsT5io_MhemYrTodCTMXbic0G_RJZtSv5HNqpqYc2h3DW3xERMbbEXofQnBsVtYnKzpxyJtQHnSuSQ9ScUoHpxyjpTSbjj0EA)**


