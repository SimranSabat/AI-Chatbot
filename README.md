# 💬 AI Chatbot — Streamlit + OpenAI

A conversational AI chatbot built with **Python**, **Streamlit**, and **OpenAI's GPT-3.5**. 
Supports multi-turn conversations with a clean, minimal chat UI.

## 🚀 Features

- 🤖 Powered by OpenAI GPT-3.5-turbo
- 💬 Multi-turn conversation memory
- ⚡ Real-time streaming responses
- 🖥️ Clean Streamlit web interface
- 🔑 Secure API key handling via environment variables

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

## ⚙️ Setup & Run

1. **Clone the repo**
```bash
   git clone https://github.com/SimranSabat/chatbot.git
   cd chatbot
```

2. **Install dependencies**
```bash
   pip install -r requirements.txt
```

3. **Add your OpenAI API key**
   Create a `.streamlit/secrets.toml` file:
```toml
   OPENAI_API_KEY = "your-api-key-here"
```

4. **Run the app**
```bash
   streamlit run streamlit_app.py
```

## 📁 Project Structure
```
chatbot/
├── streamlit_app.py     # Main application
├── requirements.txt     # Dependencies
└── .streamlit/
    └── secrets.toml     # API keys (not committed)
```

## 🔒 Security Note

Never commit your API key. Use `.streamlit/secrets.toml` locally 
and Streamlit Cloud's secrets manager for deployment.

---
Made with ❤️ by [Simran Sabat](https://github.com/SimranSabat)
