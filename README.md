

## 🧠 Conversational AI Chatbot with Memory

This is a small personal project where I built a chatbot that can **remember previous messages** during a conversation.
It uses the **Hugging Face API** with a **Gradio interface**, and runs inside Google Colab.

The aim was to move beyond a simple one-reply chatbot and make something that can follow a real chat — for example remembering someone’s name or favorite food after they say it.

---

### 🔗 Live Demo

You can test it here (available when Colab session is active):

👉 **[https://e6b93e5fccdfe26856.gradio.live/](https://e6b93e5fccdfe26856.gradio.live/)**

---

### 🌟 Features

* Replies like a normal assistant
* Remembers past messages in the conversation
* Simple memory system (stores user + bot messages)
* Clean Gradio chat interface
* Easy to run inside Google Colab

---

### 🧰 Tech Used

* Python
* Hugging Face Inference API
* Llama-3 model
* Gradio
* Google Colab

---

### 🧠 How Memory Works

Every message from the user (and every bot reply) is saved in a list.
Each time the model is called, the entire chat history is passed again — this allows the model to “remember” what was said earlier and respond with context.

---

### ▶️ How to Run

#### Install required packages

```bash
pip install gradio openai
```

#### Add your Hugging Face API Key

```python
import os
os.environ["HF_API_KEY"] = "your_key_here"
```

#### Run the script

```bash
python app.py
```

A link will appear — open it to start chatting.

---

### 💬 Short Example

**User:** My name is Sarah and I love pizza.
**Bot:** Great to meet you Sarah! Pizza is always a good choice.

**User:** What’s my name?
**Bot:** Your name is Sarah.

**User:** What do I love?
**Bot:** You love pizza.

---

### 📸 Screenshot


```markdown
![Screenshot ](https://github.com/user-attachments/assets/bcb35ff2-7399-4ed7-a4c4-c8ad8514b2e0)

```

---

### 👤 Author

**Okediran TOPE EMMANUEL**
Data Science & AI Enthusiast

This project is part of my journey toward building real AI systems and understanding conversational memory.

---

### 🚀 Future Upgrades

* Better memory handling
* Optional long-term storage
* Permanent deployment (Hugging Face Space)
* Voice mode (speech-to-text + text-to-speech)

---

If you like the project, dropping a ⭐ on GitHub means a lot!

---
