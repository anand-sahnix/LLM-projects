# AI Voice Assistant — Speech → LLM → Speech

A beginner-friendly complete project based on the **LLMs Meet Speech** concept.

## What it does
- Text mode: Text → LLM → Text-to-Speech → Play/Download MP3
- Voice mode: Microphone → Speech-to-Text → LLM → Text-to-Speech → Play/Download MP3

## Run locally
```bash
## 1. Create a virtual environment
python -m venv .venv

## 2. Activate the virtual environment

# 2.1 For Windows CMD:
.venv\Scripts\activate

# 2.2 For Windows PowerShell:
.venv\Scripts\Activate.ps1

# 2.3 For Linux/Mac/Git Bash:
source .venv/bin/activate

# 3. Install required packages
pip install -r requirements.txt
```

Copy `.env.example` to `.env` and add your API key, then:
```bash
# 5. Start the application
uvicorn app.main:app --reload
```
Open http://127.0.0.1:8000



## flow
Speech → STT → LLM → TTS → Speech

## Extensions
- RAG knowledge base
- conversation history
- multiple languages
- selectable voices
- tool calling
- streaming
