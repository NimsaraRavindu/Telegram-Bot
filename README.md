🤖 Jokers Rules Bot – Telegram Joke Bot

A fun Telegram bot that generates random jokes on any topic you give it!
Built with Python, LangChain, Groq LLM, and python-telegram-bot, this bot makes conversations more entertaining by delivering AI-generated jokes.

📑 Table of Contents

Features

How It Works

Setup Instructions

Environment Variables

Usage

Technologies Used

License

🌟 Features

Generates one funny joke about any topic you mention.

Works directly in Telegram chats.

Uses LangChain + Groq LLM (Gemma2-9b-It) for AI joke generation.

Friendly commands:

/start → Welcome message

/help → How to use the bot

@Jokers_rules_bot topic → Get a joke on a topic

🔧 How It Works

User mentions the bot in Telegram with a topic (e.g., @Jokers_rules_bot cats).

The bot builds a LangChain pipeline with a system prompt and user query.

The query is sent to Groq LLM (Gemma2-9b-It).

The bot replies with one short joke about the topic.

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/your-username/jokers-rules-bot.git
cd jokers-rules-bot

2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # On Linux/Mac
venv\Scripts\activate      # On Windows

3️⃣ Install dependencies
pip install -r requirements.txt

4️⃣ Create a .env file
TELEGRAM_API_KEY=your_telegram_bot_token
GROQ_API_KEY=your_groq_api_key
LANGCHAIN_API_KEY=your_langchain_api_key
LANGCHAIN_PROJECT=jokers-bot

5️⃣ Run the bot
python bot.py

🔑 Environment Variables
Variable	Description
TELEGRAM_API_KEY	Telegram Bot API token from @BotFather

GROQ_API_KEY	API key for Groq LLM
LANGCHAIN_API_KEY	LangChain API key
LANGCHAIN_PROJECT	Project name for LangChain (optional but useful)
🚀 Usage

Start the bot in Telegram with /start.

Mention the bot with a topic:

@Jokers_rules_bot trees


The bot replies with a funny joke about trees.

🛠 Technologies Used

Python

python-telegram-bot

LangChain

Groq LLM

⚖ License

MIT License © 2025
