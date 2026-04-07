# chatbot

## Setup

Create and activate a virtual environment, then install the project dependencies:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run

Make sure Ollama is running locally and the `gemma3:1b` model is available, then start the chatbot:

```bash
python main.py
```