# SupportMindAI

An open-source AI customer support agent that:
- 🧠 Remembers users across sessions using vector memory
- ❤️ Adjusts tone using real-time empathy/sentiment detection

Built using LangChain, OpenAI, Pinecone, and HuggingFace.

## Features
- Persistent memory (via Pinecone)
- Empathetic responses (sentiment-aware tone)
- Supports basic FAQ handling and escalation fallback

## Setup

1. Clone this repo
2. Create `.env` file with:OPENAI_API_KEY=your_key PINECONE_API_KEY=your_key
3. Install dependencies:
```bash
pip install -r requirements.txt

