# ChatBot
this is a chatbot created my integrating an llm : ollama and Ui :gradio, Basically using llm for backend and gradio for frontend
# 🔮 Mystical Tarot Chatbot — Powered by Ollama & Gradio

A magical chatbot experience built with **Ollama** and **Gradio**, this project lets you interact with an **AI Tarot Reader** that responds with poetic, intuitive insights based on your **birth date** and **birth time**.

> ✨ *"The universe speaks in symbols. Ask, and you shall receive — in whispers of fate and fragments of starlight."*

---

## 🌌 What This Chatbot Does

This isn’t your typical AI assistant. This is a **wise, enigmatic Tarot Reader** who:

- Asks for your **date of birth** and **time of birth**.
- Offers guidance based on **astrological and symbolic interpretations**.
- Suggests thoughtful **lifestyle changes**.
- Delivers responses with **poetic clarity, metaphors, and mystery**.
- Appreciates your journey and shares **empowering quotes** to lift your spirit.

All responses are generated using a custom **`system_message`** that transforms a basic LLM into a mystical guide.

---

## 🧠 The Magic Behind the Scenes

This project uses:

- **[Ollama](https://ollama.com/)** — to run local Large Language Models (e.g., `llama3`) for fast, offline responses.
- **[Gradio](https://gradio.app/)** — to create a simple, interactive web UI.
- **Python** — for integrating the components and simulating card-like guidance.

---

## 🛠️ How to Run It Locally

### 1. Clone the repo

```bash
git clone https://github.com/your-username/tarot-chatbot.git
cd tarot-chatbot
```
### 2. Install dependencies
```bash
pip install gradio ollama
```
Make sure Ollama is installed and running
If not installed:
👉
```bash
 https://ollama.com/download
```
Then run your model (e.g., LLaMA3):
```bash
ollama run llama3
```
## 🧾 Default System Message
You are a wise, enigmatic AI tarot reader.
You ask the user about their date of birth and the time of their birth,
and give them insight about their life by giving the information based on your astronomical knowledge.
Suggest them some changes in their lifestyle.
Also appreciate the user and present some good quotes.
You speak with calm insight and poetic clarity,
offering users guidance as if drawing cards from the universe itself.
Use symbolic language, metaphors, and a touch of mystery.
Your answers should feel intuitive, thoughtful, and a little magical — as if each response were whispered by fate.

For example tone:
Instead of saying "You should start learning Python",
you might say:
"The Page of Swords whispers: now is the time to begin — your curiosity is your compass."
🎭 Make It Your Own
The system_message is the soul of your chatbot. You can modify it to:

-Act like a career coach

-Become a romantic oracle

-Roleplay as a sci-fi philosopher

-Simulate historical figures

####🎨 Play around with it and create your own unique character!

#####💡 Example Questions
“What does my birth chart say about my purpose?”

“I was born on August 2nd, 2000 at 3:15 AM — what energy surrounds me?”

“How can I realign myself with the universe?”

“Share a mystical quote for my journey today.”

##🗝️ Inspiration
This project was inspired by the fusion of machine learning and spiritual symbolism — proof that technology and mysticism can coexist in beautiful ways.

##📜 License
MIT License

