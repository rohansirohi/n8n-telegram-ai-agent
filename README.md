# Telegram AI Agent using n8n + Groq

A Telegram AI chatbot workflow built using n8n automation and Groq LLM integration.

This workflow receives Telegram messages, processes them through an AI agent, stores short conversation memory, and automatically replies back to the user.

---

## Features

* Telegram bot integration
* AI-generated responses
* Conversation memory
* Automated workflow execution
* Low-code AI automation

---

## Tech Stack

* n8n
* Telegram Bot API
* Groq API
* Simple Memory Node

---

## Workflow Overview

1. User sends a message in Telegram
2. Telegram Trigger starts the workflow
3. AI Agent processes the input
4. Groq model generates a response
5. Memory stores conversation context
6. Telegram node sends response back

---

## Workflow Screenshot

![Workflow](screenshots/workflow.png)

---

## Example Telegram Chat

![Telegram Chat](screenshots/telegram-chat-example.png)

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/n8n-telegram-ai-agent.git
```

### 2. Import Workflow into n8n

Import the workflow JSON file:

```text
workflow/telegram-ai-agent.json
```

### 3. Configure Credentials

You will need:

* Telegram Bot Token
* Groq API Key

Add them inside your n8n credentials section.

### 4. Activate Workflow

Run the workflow and send a message to your Telegram bot.

---

## Environment Variables

Example:

```env
GROQ_API_KEY=your_groq_api_key
TELEGRAM_BOT_TOKEN=your_telegram_bot_token
```

---

## Future Improvements

* Web search tools
* Better memory handling
* Voice support
* Command routing
* Database integration

---

## Learning Notes

This project was originally inspired by a Telegram chatbot tutorial workflow and later modified to use Groq instead of OpenAI.

---

## License

MIT
