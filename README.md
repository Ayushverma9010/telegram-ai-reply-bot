# Telegram AI Auto-Reply Bot (Powered by Ollama)

This project is a Telegram auto-reply bot that uses locally hosted AI models through Ollama. It works with your **personal Telegram account** and responds to incoming messages using large language models such as LLaMA 3, Mistral, or others that can run offline on your machine.

# Telegram AI Auto-Reply Bot (Powered by Ollama)

This project is a Telegram auto-reply bot that uses locally hosted AI models through Ollama. It works with your personal Telegram account and responds to incoming messages using large language models such as LLaMA 3, Mistral, or others that can run offline on your machine.

## Features

- Works with personal Telegram accounts via Telethon
- Uses Ollama to run AI models locally on your machine
- Completely offline and private—no third-party APIs or internet dependency
- Automatically replies to incoming messages

## Prerequisites

- Python 3.9 or higher
- Ollama installed and running
- Telegram API credentials (API ID and API Hash)

## Installation

### 1. Install Ollama

Download Ollama from: https://ollama.com/download

Start a model (e.g., LLaMA 3):

```
ollama run llama3
```

### 2. Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/telegram-ai-ollama-bot.git
cd telegram-ai-ollama-bot
```

### 3. Install Dependencies

```
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Rename `.env.example` to `.env` and fill in your credentials.

### 5. Run the Bot

```
python main.py
```
