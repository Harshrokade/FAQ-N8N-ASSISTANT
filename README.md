# 🤖 Automated FAQ Assistant (n8n + OpenAI)

This project is an **AI-powered FAQ assistant** built with **n8n**.  
It reads a company FAQ file, generates embeddings, and automatically assists clients with accurate answers via chat platforms like **Telegram/Slack/Website**.  

---

## 🚀 Features
- Reads FAQ documents and builds embeddings.
- Uses **OpenAI** to answer client questions based only on FAQ content.
- Provides polite fallback response when an answer is not found.
- Can be connected to **Telegram, Slack, or Webchat**.

---

## 🛠️ Tech Stack
- [n8n](https://n8n.io) – Workflow Automation
- OpenAI Embeddings – AI-powered search
- Vector Store (e.g., Pinecone, Qdrant, Supabase) – For storing embeddings
- Telegram/Slack Integration – For client-facing chat

---

## 📸 Workflow Preview
![Workflow Screenshot](./workflow/Screenshot.pnj)

---

## 🔄 Workflow Export
The complete n8n workflow is available here:  
👉 [faq-assistant.json](./workflows/faq-assistant.json)

You can **import this JSON into n8n** to try it yourself.

---


---

## 📌 Example Use Case
**Client:** *“How do I reset my password?”*  
**Bot:** *“You can reset your password by going to the account settings page and clicking ‘Forgot Password’. A reset link will be sent to your email.”*  

---

## 👨‍💻 Author
**Harsh Rokade**  
- [LinkedIn](https://linkedin.com/in/YOUR_PROFILE)  
- [GitHub](https://github.com/YOUR_GITHUB)  
