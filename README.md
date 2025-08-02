# 🧠 BaatKaro – Conversational AI Chatbot

A general-purpose conversational chatbot powered by **LangGraph** and an LLM. Supports memory and persistence for continuous, context-aware dialogue. Includes a simple UI built with **Streamlit**.

## 🚀 Features

- 🗣️ Human-like conversation using LLM (e.g., Gemma, GPT, or Command R+)
- 🧠 Memory integration for context tracking
- 💾 Persistent chat history using LangGraph memory saver
- 💡 Streamlit-based frontend for interactive chatting
- 🔐 `.env` support for secure API key handling

## 🛠️ Tech Stack

- **LangGraph**
- **LangChain**
- **LLM (Gemma)**
- **Python**
- **Streamlit**

## ⚙️ Setup Instructions

# 1. Clone the repo
git clone https://github.com/srivastavankur1/BaatKaro.git
cd BaatKaro

# 2. Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# 3. Install dependencies
pip install -r requirements.txt

# 4. Add your API key in a .env file
OPENAI_API_KEY=your-key-here

# 5. Run the chatbot
streamlit run frontend.py

