# 🤖 Enhanced Q&A Chatbot with Ollama & LangChain

A locally-powered Q&A chatbot built with [Streamlit](https://streamlit.io/), [LangChain](https://www.langchain.com/), and [Ollama](https://ollama.com/) — no cloud API keys required. Run powerful LLMs entirely on your own machine.

---

## ✨ Features

- 🧠 **Multiple LLM Support** — Switch between `mistral`, `gemma2`, and `phi3` models
- 🎛️ **Adjustable Parameters** — Control `temperature` and `max tokens` via interactive sidebar sliders
- 🔍 **LangSmith Tracing** — Built-in LangChain observability for monitoring and debugging
- ⚡ **Fully Local** — All inference runs via Ollama on your local machine
- 🖥️ **Clean Streamlit UI** — Simple and intuitive chat interface

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Streamlit](https://streamlit.io/) | Web UI framework |
| [LangChain](https://www.langchain.com/) | LLM orchestration & prompt chaining |
| [Ollama](https://ollama.com/) | Local LLM inference engine |
| [LangSmith](https://smith.langchain.com/) | Tracing & observability |
| [python-dotenv](https://pypi.org/project/python-dotenv/) | Environment variable management |

---

## 📋 Prerequisites

- Python 3.9+
- [Ollama](https://ollama.com/download) locally
- A [LangSmith](https://smith.langchain.com/) for tracing

---


## 📁 Project Structure

```
ollama-qa-chatbot/
│
├── app.py                  # Main Streamlit application
├── .env                    # Environment variables (not committed)
├── .env.example            # Example env file
├── requirements.txt        # Python dependencies
├── .gitignore              # Git ignored files
└── README.md               # Project documentation
```

---

## 📦 Requirements

Create a `requirements.txt` with the following:

```
streamlit
langchain
langchain-core
langchain-community
ollama
python-dotenv
```

---

## 🖥️ Usage

1. **Select a Model** from the sidebar dropdown (`mistral`, `gemma2`, `phi3`)
2. **Adjust Temperature** — Higher values (closer to 1.0) give more creative responses; lower values are more focused
3. **Set Max Tokens** — Controls the maximum length of the response
4. **Type your question** in the input box and press Enter

---



- [Ollama](https://ollama.com/) for making local LLMs accessible
- [LangChain](https://www.langchain.com/) for the powerful LLM framework
- [Streamlit](https://streamlit.io/) for the easy-to-build UI
