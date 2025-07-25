# Telegram ChatGPT Bot

A simple Telegram chatbot powered by OpenAI’s GPT-3.5-turbo, built with [aiogram](https://github.com/aiogram/aiogram).

## Features

- Responds to `/start`, `/help`, and `/clear` commands
- Maintains simple conversation state for back-and-forth chats
- Integrates with OpenAI’s Chat Completion API (GPT-3.5-turbo)
- Easily extendable for your own features

## Getting Started

### 1. Clone the repository
```
bash
git clone https://github.com/yourusername/telegram-gpt-bot.git
cd telegram-gpt-bot
```

### 2. Install requirements
We recommend using a virtual environment:

```
bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

### 3. Set up environment variables
Create a .env file in your project root:

```
OPENAI_API_KEY=your-openai-api-key-here
TELEGRAM_BOT_TOKEN=your-telegram-bot-token-here
```

### 4. Run the bot
```
bash
python research/echo_bot.py
```

### Commands
/start – Start the conversation

/help – Show available commands

/clear – Clear previous conversation context

### Requirements
Python 3.8+

aiogram

openai

python-dotenv

### Install them with:

```
pip install aiogram openai python-dotenv

```

### Notes
You must have a Telegram Bot Token and an OpenAI API key.

For privacy, never commit your .env file or keys to public repositories!
