
---

## 🧠 Conversational AI Chatbot with Memory

This is a small personal project where I built a chatbot that can **remember previous messages** in a conversation.
It uses the **Hugging Face API** and a **Gradio interface**, and it runs in Google Colab.

The goal was to move from a basic one-shot chatbot to something that can understand and follow a continuous discussion — for example, remembering someone’s name or favorite food after they mention it.

---

### 🔗 Live Chat Demo

You can test the chatbot here (works when Colab session is running):

👉 [https://e6b93e5fccdfe26856.gradio.live/](https://e6b93e5fccdfe26856.gradio.live/)

---

### 🌟 What This Chatbot Can Do

* Respond like a normal AI assistant
* Remember earlier parts of the conversation
* Hold simple personal context (e.g., “My name is Sarah”)
* Display a friendly Gradio interface
* Works easily in Google Colab

---

### 🧰 Tools and Technologies

* **Python**
* **Hugging Face Inference API**
* **Llama-3.1 model**
* **Gradio**
* **Google Colab**

---

### 📌 How the Memory Works

Each time the user sends a message, it gets stored in a list.
When the model replies, that is also added.
So over time, the model sees the full chat history and can refer back when needed.

---

### ▶️ Running the Project

#### **Install needed packages**

```bash
pip install gradio openai
```

#### **Add your Hugging Face key**

```python
import os
os.environ["HF_API_KEY"] = "your_HF_key_here"
```

#### **Run the script**

```bash
python app.py
```

This will open a link in your browser where you can chat with the bot.

---

### 💬 Example Conversation

```
User: Hello, my name is Sarah and I love pizza.
Bot: Nice to meet you Sarah! Pizza is a great choice.

User: What is my name?
Bot: Your name is Sarah.

User: What do I love?
Bot: You love pizza.
```

---

### 📸 Screenshot

```markdown
### Screenshot
![Chatbot Demo](./Screenshot.jpg)
```


---

### 👤 Creator

**Name:** Okediran TOPE EMMANUEL
**Field:** Data Science / AI

This project is part of my practice in building real AI applications and improving my understanding of how chat memory works.

---

### 🙌 Notes

Still planning to explore:

* Making the memory longer and smarter
* Optional database storage
* Deploying permanently on Hugging Face Spaces
* Adding voice input/output later

---

### ⭐ If you like this project

A star on GitHub would be appreciated!

---

