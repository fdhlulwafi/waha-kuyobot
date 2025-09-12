# WAHA-Chatbot 🤖💬

A WhatsApp smart chatbot designed using **[WAHA](https://github.com/devlikeapro/waha)** and **[n8n](https://n8n.io/)** workflows to interact intelligently and enhance user experience.  

![WAHA Workflow](WorkflowWAHA.png "WAHA Workflow")

---

## 🚀 Features
- **Two Modes of Operation**
  - **Personal Mode** 🗣️  
    - Chat like a normal AI chatbot  
    - Transcribe text from images  
  - **Group Mode** 👥  
    - Works like a Discord-style bot, responding to commands  

---

## 📜 Available Commands (Group Mode)
- `/help` → Show available commands  
- `/search <query>` → Get information from the web via Google Search API  
- `/image <attach>` → Transcribe text from an image  
- `/song <title or YouTube link>` → Download a song by title or YT link  

---

## 📦 Requirements
- WAHA (WhatsApp HTTP API)  
- n8n workflow automation  
- Google Search API key  
- YouTube API key (for songs)  
- OpenAI API key (optional, for chatbot mode)  

---

## 🙏 Credits
- [WAHA](https://github.com/devlikeapro/waha) for WhatsApp integration  
- [n8n](https://n8n.io/) for workflow automation  
- APIs: Google Search, YouTube, OpenAI  

---

## 💡 Future Ideas
- Add more group commands (polls, reminders, translation, etc.)  
- Connect with external APIs for weather, news, and more  
- Improve personal mode with context memory  
