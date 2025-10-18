# Retrieval-Augmented-Generation-RAG-chatbot

An open-source, clean & customizable **RAG (Retrieval-Augmented Generation) chatbot workflow** built using [n8n](https://n8n.io/), designed for both end users and developers.  

- **End users:** Chat with your documents directly through **WhatsApp** for context-aware AI responses.  
- **Developers:** Build, customize, and extend your own RAG pipelines using n8n nodes and Gemini LLM.  

---

## Preview / Demo

<img width="1918" height="971" alt="Rag Agent In whatsApp" src="https://github.com/user-attachments/assets/924c14b8-baea-4858-86c8-cc94e582ca98" />



---

## Features

### For End Users

- **Intelligent QA on Documents:** Ask questions via WhatsApp and get context-aware responses from your documents.  
- **Gemini LLM Support:** Powered by Gemini API for advanced AI reasoning and retrieval.  
- **Easy Setup:** Import the n8n workflow JSON and configure your credentials to start chatting.  

### For Developers

- **RAG Pipeline Framework:** Build and customize your own RAG-based document QA workflows.  
- **Customizable n8n Nodes:** Modify workflows to fit your unique use case.  
- **Extensible Workflows:** Integrate new data sources, APIs, and processing steps easily.  

### Key Features

- Multi-source document retrieval using vector databases  
- Context-aware AI responses via Gemini LLM  
- WhatsApp chatbot interface  
- Configurable prompts and settings  
- Hybrid retrieval pipelines (full-text + vector search)  
- Modular and extensible for developers  

---

## Installation

### System Requirements

- n8n (latest version)  
- Node.js environment  
- Gemini API key  
- Vector database (e.g., Supadata base,Pinecone)  
- WhatsApp API/Integration credentials  

### Using Docker (optional)

You can run your RAG Chatbot workflow in Docker:

```bash
docker run -v ./workflow_data:/app/data -p 5678:5678 -it --rm your-docker-image-name
