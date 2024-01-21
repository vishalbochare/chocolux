 ## Microsoft-Future-Ready-Talent-Virtual-Internship-Project
## Project Title: Chocolux Website 
## **Chapter-I**
## Objective

In this project, I would be using QnA Maker Service to make a Chatbot that give solution and answer your question.
## Problem Statement
Develop a Chatbot for Chocolux Website that solve the customer problems realted to the website and chocolates. 
## Problem Context
The purpose of chat bots is to support and scale business teams in their relations with customers. It could live in any major chat applications like Facebook Messenger, Slack, Telegram, Text Messages. Chatbot applications streamline interactions between people and services, enhancing customer experience. At the same time, they offer companies new opportunities to improve the customers engagement process and operational efficiency by reducing the typical cost of customer service. This project is focussed on building a custom chatbot that will be your fundamental step of the learning curve of building your own professional chatbots.
## What is a Microsoft Azure QnA Maker Service?
QnA Maker is a cloud-based Natural Language Processing (NLP) service that allows you to create a natural conversational layer over your data. It is used to find the most appropriate answer for any input from your custom knowledge base (KB) of information.
QnA Maker is commonly used to build conversational client applications, which include social media applications, chat bots, and speech-enabled desktop applications.
QnA Maker does not store customer data. All customer data (question answers and chat logs) is stored in the region the customer deploys the dependent service instances in. For more details on dependent services see here.
This documentation contains the following article types:
• The quickstarts are step-by-step instructions that let you make calls to the service and get results in a short period of time.
• The how-to guides contain instructions for using the service in more specific or customized ways.
• The conceptual articles provide in-depth explanations of the service's functionality and features.
• Tutorials are longer guides that show you how to use the service as a component in broader business solutions.
When to use QnA Maker
• When you have static information - Use QnA Maker when you have static information in your knowledge base of answers. This knowledge base is custom to your needs, which you've built with documents such as PDFs and URLs.
• When you want to provide the same answer to a request, question, or command - when different users submit the same question, the same answer is returned.
• When you want to filter static information based on meta-information - add metadata tags to provide additional filtering options relevant to your client application's users and the information. Common metadata information includes chit-chat, content type or format, content purpose, and content freshness.
• When you want to manage a bot conversation that includes static information - your knowledge base takes a user's conversational text or command and answers it. If the answer is part of a pre-determined conversation flow, represented in your knowledge base with multi-turn context, the bot can easily provide this flow.


After you publish your knowledge base, a client application sends a user's question to your endpoint. Your QnA Maker service processes the question and responds with the best answer.
## Problem’s Primary Goals
•  Setting up a chatbot that can order your requirements.

•  Using a QnA Maker Bot service to build a chatbot for Website. 

## Input
For input source i use a Editorial custom question and answer type.
## Output
![Picture2](https://user-images.githubusercontent.com/71881295/160243365-5a79dd46-15e2-4473-a12a-858ec57929d1.png)
![image](https://github.com/srush2906/chocolux/assets/115866345/6e024fbc-578b-47b1-97b3-24a9e003a4a4)
![image](https://github.com/srush2906/chocolux/assets/115866345/20b64ef6-da2c-4e9c-9d01-b48d2e4bc448)


## **Chapter-II**

## Microsoft Azure Bot Framework Architecture(Resource visualizer)

 ![image](https://github.com/srush2906/chocolux/assets/115866345/27c74a35-f901-441e-bf94-d030e1bfc49a)


  
## Microsoft Azure QnA Maker Development Cycle

![Picture19](https://user-images.githubusercontent.com/71881295/160243758-0622438b-ed0d-4ed0-a9fa-15922a56d8f0.png)

## Life Cycle of a Conversational Bot

![Picture20](https://user-images.githubusercontent.com/71881295/160243891-a71ddc39-a436-444f-9dd1-0fcbed88fc5f.png)

### How to build a bot
Azure Bot Service and the Bot Framework offer an integrated set of tools and services to facilitate the building process. Choose your favorite development environment or command line tools to create your bot. SDKs exist for C#, Java, JavaScript, Typescript, and Python. We provide tools for various stages of bot development to help you design and build bots.
### Plan
As with any type of software, having a thorough understanding of the goals, processes and user needs is important to the process of creating a successful bot. Before writing code, review the bot design guidelines for best practices and identify the needs for your bot. You can create a simple bot or include more sophisticated capabilities such as speech, natural language understanding, and question answering.
### Build
Your bot is a web service that implements a conversational interface and communicates with the Bot Framework Service to send and receive messages and events. Bot Framework Service is one of the components of the Azure Bot Service and Bot Framework. You can create bots in any number of environments and languages.

![Picture34](https://user-images.githubusercontent.com/71881295/160243991-2104e9b0-7dd4-4df7-a65c-7e41ba4913ad.png)
### Test
Bots are complex apps with a lot of various parts working together. Like any other complex app, this can lead to some interesting bugs or cause your bot to behave differently than expected. Before publishing, test your bot. We provide several ways to test bots before they are released for use:
• Test your bot locally with the emulator. The Bot Framework Emulator is a stand-alone app that not only provides a chat interface but also debugging and interrogation tools to help understand how and why your bot does what it does. The Emulator can be run locally alongside your in-development bot application.
• Test your bot on the web. Once configured through the Azure portal your bot can also be reached through a web chat interface. The web chat interface is a fantastic way to grant access to your bot to testers and other people who do not have direct access to the bot's running code.

### Publish
When you are ready for your bot to be available on the web, publish your bot to Azure or to your own web service or data center. Having an address on the public internet is the first step to your bot coming to life on your site, or inside chat channels.

### Connect
Connect your bot to channels such as Facebook, Messenger, Kik, Slack, Microsoft Teams, Telegram, text/SMS, and Twilio. Bot Framework does most of the work necessary to send and receive messages from all these different platforms - your bot application receives a unified, normalized stream of messages regardless of the number and type of channels it is connected to. For information on adding channels, see channels topic.

### Evaluate
Use the data collected in Azure portal to identify opportunities to improve the capabilities and performance of your bot. You can get service-level and instrumentation data like traffic, latency, and integrations. Analytics also provides conversation-level reporting on user, message, and channel data.

## Decision Making Between LUIS and QnA Maker

### When to use the QnA Maker?

If your organization has lots of static questions and answers), take advantage of out of the box features of QnA Maker. Upload your static questions and answers into QnA Maker Portal, and your application can call QnA API to search for questions asked by the user on the front-end application and return the response.

### When to use the LUIS?

If you would like to design the application which needs to extract the information from the user’s questions and further process their intents, then use the LUIS.

## Process

<img width="452" alt="Picture21" src="https://user-images.githubusercontent.com/71881295/160244555-43372a2c-a619-4d7a-9acc-b72bdfbab9f2.png">

## Task 1

### Create a Resource Group on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/c2b01caf-a8d3-4e56-9f7f-852892b6a9ab)


## Task2

### Create a Language Service on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/dd4c5369-61ad-4703-a35d-a3f230326777)

## Task3

### Create a Knowledge Base on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/7a725499-b11c-400f-b9c2-6bbc20ccf6ff)


## Task4

### Create an App Service on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/ec630902-f8b0-4c94-b47f-1350777eb063)


## Task5

### Create a Web App Bot on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/bbc9ed06-247f-4921-ae86-df3c5a6bf6d4)


## Task6

### Testing my Bot on Azure

![image](https://github.com/srush2906/chocolux/assets/115866345/ee3e08e8-bff0-4207-9668-d7bf94c1630c)

![image](https://github.com/srush2906/chocolux/assets/115866345/fadb0032-804f-4a55-be2e-5041703791d6)

## Expected Outcome
By the end of this milestone, you would be having a working chatbot system that solve your problems about website.

## Technologies / Tools Used

• Microsoft Azure QnA Maker Service and cognitive service

• Git Hub

• Azure Storage account and App Service

• Microsoft Visual Studio


## URLs
Drive video URL:https://drive.google.com/file/d/1vVFL7uA6N9Fkc9WwrZ9HZsbRgTX7VlyL/view?usp=sharing 

PDF File With ScreenShoots and explanation about project :https://drive.google.com/drive/folders/1kcsLKG448f-JIggUoRXrAbcA1TzWuf-0?usp=sharing

working project URL: https://srush2906.github.io/chocolux/

Azure Account ID: jawale.manjusha@gmail.com

## Acknowledgements
My sincere thanks, to Microsoft for an impressive QnA Maker service on MS Azure Cloud to make the chatbot development easy.
Sincere appreciation to Team of Future Ready Talent who supported and encouraged us to work on this project.

## For questions or suggestions, please contact
[vishalbochare.3535@gmail.com]
