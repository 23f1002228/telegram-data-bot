# Telegram Data Analyst Bot

A Telegram bot built for the IIT Madras TDS Programming Assignment.

## Features

- Answers data analysis questions.
- Supports multi-turn conversations.
- Returns responses as a single JSON object.
- Includes a public `log_url` in every response.
- Logs every interaction in `run.jsonl`.
- Uses GPT-5 Mini through AIPipe.

## Tech Stack

- Python
- python-telegram-bot
- OpenAI Python SDK
- AIPipe
- Railway
- GitHub

## Response Format

Every reply is exactly one JSON object.

Example:

```json
{
  "answer": {
    "capital": "New Delhi"
  },
  "log_url": "https://raw.githubusercontent.com/23f1002228/telegram-data-bot/main/run.jsonl"
}
```

## Deployment

The bot is deployed on Railway and remains online for evaluation.

## Repository Structure

```
bot.py
requirements.txt
run.jsonl
README.md
```

## Author

Ayush Gourav

IIT Madras BS Degree Programme
