### 📁 Project 2 — RAG Knowledge Retriever

## 📌 Overview
Generates a answer of query grounded on knowledge base in Salesforce Case.It provides answer wheneven a new case is created in Salesforce using a secure FastAPI middleware, OpenAI GPT, Langchain,Langgraph,Pinecone,input guardrails, 
PII redaction, and output safety filters.

## 🎯 Problem Statement
While trying to resolve a Case in Salesforce Agent/user has to check multiple knowledge documents to figure out resolution for problem in hand. It is a time consuming process.By implementing this solution lots of time  is saved and agnet can put those efforts some other important tasks.

## 🏗️ Architecture
![architecture diagram](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/salesforce_rag_architecture.svg)

### Case Answer Output
![Case Record Summary](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_Miss_Case_Record.png)

## 🛠️ Tech Stack
- Salesforce (Apex,Flow,Rest api)
- Python/FastAPI,OpenAi,langgraph,langchain,Pinecone,Redis and render

## 📸 Screenshots

### Salesforce Flow
![Flow in Flow Builder](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_Flow.png)

### Salesforce PermissionSet
![PermissionSet](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_PermissionSet.png)

### Middleware FastApi Docs
![FastApi docs](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_FastApi.png)

### Middleware Request Response
![Request Response](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_ngrok_Req_Res.png)

### FastApi Log Output
![FastApi Log](https://github.com/sharadarona/salesforce-genai-portfolio/blob/main/assets/project2-screenshots/Screenshot_RAG_Middleware_Log.png)

## 🔗 Repos
- [Salesforce Metadata](https://github.com/sharadarona/sf-rag-knowledge-retriever)
- [Python Middleware](https://github.com/sharadarona/rag-knowledge-retrieval-api)
  
## 👩‍💻 Author
- Sharad Yadav
- GitHub:   [github.com/sharadarona](https://github.com/sharadarona)
- LinkedIn: [linked/in/sharadarona](https://linked/in/sharadarona/)

