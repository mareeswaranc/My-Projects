# 🤖 AI Agent with Long-term Memory

## Overview
This project demonstrates how to build an **AI Agent with memory** using **n8n**, **Supabase**, and **PostgreSQL**.  
The agent can recall past conversations, reference document context, and perform semantic search with embeddings.

---

## 🔑 Key Features
- **Conversation History** – Maintains memory of past chats using PostgreSQL.
- **Document Context** – Retrieves relevant information from stored documents.
- **Vector Search** – Uses Supabase Vector Store for semantic retrieval.
- **RAG (Retrieval-Augmented Generation)** – Enhances responses with contextual knowledge.

---

## 🛠 Tech Stack
- **n8n** – Workflow automation platform.
- **Supabase** – Backend + Vector Store.
- **PostgreSQL** – Memory storage for chat history.
- **OpenAI** – Language model and embeddings.

---

## ⚙️ How It Works
1. **Chat Input**: User sends a message → Triggered in n8n.
2. **Memory**: PostgreSQL stores/retrieves conversation history.
3. **RAG Agent**: Uses OpenAI + Supabase Vector Store for document retrieval.
4. **Response**: AI generates an answer based on both memory and context.

---

## 📂 Workflow Components
- **Chat Trigger**: Listens for incoming chat messages.
- **OpenAI Chat Model**: Generates responses.
- **Postgres Chat Memory**: Stores conversation history.
- **Supabase Vector Store**: Retrieves contextual knowledge from documents.
- **Embeddings**: OpenAI embeddings used for semantic search.
- **Google Drive Loader**: Example for uploading and storing documents.

---

## 🚀 Example Use Cases
- Personal AI assistant that remembers context across sessions.
- Knowledge base bot for teams (documents + memory).
- Educational assistant that recalls user queries and progress.

---

## 📌 Next Steps
- Add role-based access for users.
- Extend document loaders (PDF, Notion, Confluence).
- Build a UI for managing documents and conversations.
