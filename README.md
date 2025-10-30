
# 🤖 Conversational AI Chatbot with Memory

A simple yet powerful chatbot that **remembers past messages** and keeps context during a conversation — built with **Hugging Face API + Gradio** and run in **Google Colab**.

This project demonstrates how to move from a basic prompt-response bot to a **context-aware chatbot** that can recall things like your name or preferences as the chat continues.

---

## 🔥 Live Demo

> ✅ Works while Colab session is running  

👉 **https://e6b93e5fccdfe26856.gradio.live/**

---

## ✨ Key Features

✅ Remembers previous messages  
✅ Understands and responds with context  
✅ Lightweight chat memory system  
✅ Friendly **Gradio UI**  
✅ Runs easily in **Google Colab**

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|--------|
| 🐍 Python | Main programming language |
| 🤗 Hugging Face API | Llama-3 model inference |
| 🦙 Llama-3 | Language model |
| 🎛️ Gradio | Web chat UI |
| ☁️ Google Colab | Execution environment |

---

## 🧠 How Memory Works

The chatbot keeps a list of all messages (user + bot).  
Each time you type, the whole history is sent to the model — so it can respond with context.

It’s a simple but effective way to simulate short-term memory in AI.

---

## ▶️ Run it Yourself

### 📦 Install packages
```bash
pip install gradio openai
````

### 🔑 Add your HF API key

```python
import os
os.environ["HF_API_KEY"] = "your_key_here"
```

### 🚀 Run

```bash
python app.py
```

---

## 💬 Example Conversation

> **User:** Hi, my name is Sarah and I love pizza.
> **Bot:** Nice to meet you Sarah! Pizza sounds delicious 😄

> **User:** What's my name?
> **Bot:** Your name is Sarah.

> **User:** What do I love?
> **Bot:** You love pizza.

---

## 👨‍💻 Author

**Okediran TOPE EMMANUEL**
Data Scientist & AI Enthusiast

This project is part of my journey exploring **AI memory, conversational agents, and real-world AI deployment.**

---

## 🚀 Future Enhancements

* 🧠 Advanced memory
* 📦 Database storage
* 🌐 Deploy to Hugging Face Spaces
* 🎤 Voice chat

---


---

### Next step

✅ Tell me when you're ready — I’ll help you **add the screenshot correctly** next.
````
