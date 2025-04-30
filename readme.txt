This repo contains the project files for submission to the AI Agent Hackathon. 

## Project Overview:
This AI Agent will assist a school or university student that needs help with education related information by searching the web and returning
the outputs in a chat with a Telegram bot account. This allows a student the benefit of having the information available in one place. We 
understand that not everyone knows what they will do after school; will they forge their own path or will they go down the route of academia? 
Our tool aims to democratize knowledge not previously available to a learner especially on the African Continent.

The workflow asks for basic information about a student, i.e. their current education level and grades and profiles them based on 
that. 
 
We have implemented Telegram as the front-end and a way to interact with the model and workflow. n8n is the chosen workflow tool. 

##  Tools:
The model has access to the following tools.

Youtube API 
Gmail API
Google Drive API
SerpAPI
HTTP request to the government education website in South Africa. 
Pinecone Vector Storage
OpenAI suite (Embeddings and Chat Model)

##  Features:
A student can retrieve information about courses at various universities and the associated link to that page
A student can also retrieve Youtube video recommendations for their specific field of study (example, Khan Academy Youtube Channel for 
Mathematics help). 
Students will also receive website links pertaining to helpful courses/quizzes about their topic of study.

##  PLEASE NOTE!: 
We have created API keys on free-tier accounts (which means we are limited in the amount of queries still available to the model)
and we have used a trial version of n8n, please do try and judge our project by 9th May 2025.