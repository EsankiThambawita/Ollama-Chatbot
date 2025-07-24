# Local Chatbot Using LangChain, Ollama & Streamlit

A beginner-friendly chatbot that runs 100% locally — no API keys, no internet, and full privacy. Built using LangChain for conversation handling, Ollama to run a local LLM like `llama2`, and Streamlit for a clean user interface.

---

## 🚀 Features

- Runs entirely offline on your machine
- Uses LangChain to manage conversation and memory
- Powered by Ollama (local LLM like `llama2`)
- Streamlit front-end for user interaction
- Remembers context like your name within a session

---

## 🛠️ Tech Stack

- **LangChain** – LLM framework for chains and memory
- **Ollama** – Local language model runner (e.g., `llama2`)
- **Streamlit** – Simple front-end UI
- **Python 3.10+**

---

##  Installation

1. Clone the Repository
```bash
git clone https://github.com/your-username/local-chatbot.git
cd local-chatbot
```

2. Create and Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate # For Windows

source venv/bin/activate # For macOS/Linux
```

3. Install Python Dependencies
```bash
pip install -r requirements.txt
```

4. Install Ollama
Download and install from:
https://ollama.com

Then pull and run the LLM model:

```bash
ollama run llama2
```

5. Run the Streamlit App
```bash
streamlit run app.py
```


