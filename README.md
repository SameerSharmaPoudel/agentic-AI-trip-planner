# 🧭 Agentic AI Trip Planner

An agentic travel planning app powered by LLMs and tools. Plan your perfect trip using natural language prompts and AI assistance — all through an interactive Streamlit frontend.

## ✨ Features

- 🧠 **LLM-driven agent** to plan trips based on user goals
- 🗺️ Conversational natural-language interface
- ⚙️ Modular backend with support for new tools/APIs
- 🎨 **Streamlit UI** for easy interactivity
- ⚡ Fast LLM response via Groq API or other APIs  

---

## 📦 Installation

### Clone the repo

```bash
git clone https://github.com/yourusername/agenticai_trip_planner.git
cd agenticai_trip_planner
```

### Create a virtual environment and activate it (for Windows as below)

```bash
python -m venv .venv
.venv\Scripts\activate
```

### Install dependencies (recommended using uv)

```bash
uv pip install -r requirements.txt
```

## ▶️ Usage

### Set API keys as environment variables

Put the keys of the required APIs in a .env file and load it with dotenv.

### Run Streamlit frontend

 ```bash
streamlit run streamlit_app.py
```

### Run FastAPI backend


 ```bash
uvicorn main:app --reload --port 8000
```
