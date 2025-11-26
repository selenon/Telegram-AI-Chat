# Telegram AI Chat

A Python-based Telegram bot that provides intelligent conversational responses using Pyrogram.

## Setup

### Prerequisites

- Python 3.7+
- A Telegram Bot Token from [@BotFather](https://t.me/BotFather)
- API keys for your chosen AI service (e.g., OpenAI, Anthropic, or others)

### Installation

1. **Clone and enter the repository**
   ```bash
   git clone https://github.com/selenon/telegram-ai-chat.git
   cd telegram-ai-chat
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure the bot**
   ```bash
   cp sample_config.py config.py
   ```
   Edit `config.py` with your actual credentials:
   - `API_ID` and `API_HASH` from [my.telegram.org](https://my.telegram.org)
   - `BOT_TOKEN` from BotFather
   - AI service API keys and configuration

4. **Run the bot**
   ```bash
   python luna.py
   ```

## Deployment

### Heroku

Click the button below to deploy directly to Heroku:

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

### Docker

Build and run with Docker:

```bash
docker build -t telegram-ai-chat .
docker run -d telegram-ai-chat
```

## Configuration

The `sample_config.py` contains all necessary environment variables. Key settings include:

- Telegram API credentials
- Bot token
- AI API configuration
- Optional settings for rate limiting and access control
