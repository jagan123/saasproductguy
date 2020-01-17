---
title: "Tech Cheatsheet for the Non Technical PM"
date: 2020-01-17T08:00:26+05:30
draft: false
---

If you are from a non CS background, but are venturing into technical product management you might find it overwhelming to communicate with your engineers. Here's a quick list of tech jargon that makes it easy to get an undetstanding of how the tech side of things work.

### API - 
Application Programming Interface.  All modern apps backend is created using APIs so it’s easy for one or more applications to talk with each other. All actions a user does on an app invokes multiple APIs and their response determine how the frontend UI has to render and show results accordingly. 

Earlier SOAP and XML used to be the standdard response formats of APIs. But over the last decade, JSON format for the responses took over and is more likely a standard for all applications built on modern tech stack.

### 
JSON response - 
A key:value pair response when an API is accessed. e.g: { name: Jagan, email: jagan.ganti@gmail.com} could be a response when you hit an API.
In the above format, the word before the colon is called ‘key’ and the one later is called ‘value’. Hence it’s _key:value_ pair.
<link to GET weather api url>

### ErrorCodes -
404 - Server not found.  
500 - Server unavailable / down.  
501 - Permanent redirect.  
### 
### Postman -
A tool to quickly access the available APIs, without writing any front-end code.

### CRUD
Create, Read, Update, Delete operations are performed with the help of the following methods on the APIs

GET  - get all records or details of a particular record. 
POST/PUT  - create a new record or update an existing record
DELETE  - delete all or any given record id in a table

If you have an excel sheet as a database, GET would fetch this list, POST is to create a new row in the excel sheet and with DELETE you can remove any row id in the sheet. The output can be in JSON format.

### Authentication -
Allowing users to login to your application (app).  
oAuth  

### Authorization -
An authenticated user is authorised to access certain pages/ apis of your application. 

### Backend - 
The code logic of your application is written here.
e.g languages: Nodejs, Python, java, Ruby

### FrontEnd -
No logic. The presentation layer or the “view” for the end user is written here. 
e.g languages: html, css, react, vue 

### Library & Framework -
Here’s a great explanation in stack overflow that talks about the differences between library and framework
[terminology - What is the difference between a framework and a library? - Stack Overflow](https://stackoverflow.com/questions/148747/what-is-the-difference-between-a-framework-and-a-library)

### Git -
A standard to have proper code versioning in a development team. Svn is another way - old now. This allows multiple people to use the same code base and make changes without ones change affecting the other. Every developer branches out, makes changes to their files and raises a “pull’ request. These branches (folders) gets merged to the main branch (often called master). 

Here’s a 10 minute read - [Git Handbook · GitHub Guides](https://guides.github.com/introduction/git-handbook/)

### PR -
Raising a PR == Raising a pull request.

### Github & others - 
Github, bitbucket, gitlab are the services used to store your git projects online. 

### Code review -
When a developer works on a feature branch or fixes a defect, raises a PR (pull request) for a peer / team lead to go through, review the code and either merge it to master or ask for more explanation through comments in GitHub. 

### Build -
Jenkins - a build process tool. Every code base, either frontend or backend of an application, go through a “build” process to get the final binary/output that can be consumed by an end user. 

### Code coverage -
% of code coverage done. Amount of APIs / functions that have test cases written

### Testing -
Visual testing, unit testing, automation testing

### Configuration -
Environment variables, config json files etc
Why are these used? - Say, you have an API key (think password) to access an API to get a response, putting this directly in the code is not a good practise. Instead a config / env variable file is created so this variable can be used anywhere in the code files instead of putting the direct value at all places. If this value changes, it can be changed only in the config file instead of modifying at ALL the places.

### Developer console -
Chrome dev tools, inspect element, dev extensions, play/pause debugger

### AI
Artificial Intelligence:
As a famous tweet goes, “You’d use the jargon Machine learning to hire engineers and artificial intelligence to raise VC funds”
Think: 

### VR
Virtual Reality: This need you to have a VR glasses to view the content. The content format has to support and can be played on a device with a monitor.    
Think, Snap glasses!

### AR
Augmented Reality: Here, the device you wear doesn’t have a monitor, instead wearing it would augment the content on any surface which need not be a display device/monitor. 
e.g: With AR, you can start viewing/projection appear on real life objects.    
Think, Pokemon go!


That’s it for now. I will keep updating this sheet as I remember something that’s important and not present here. What do you think about this list? Let me know on [twitter](https://twitter.com/jagan123).