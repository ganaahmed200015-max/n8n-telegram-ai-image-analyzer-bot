# 🤖 Telegram AI Image Analyzer

An n8n workflow that lets users send images to a Telegram bot and receive an AI-generated analysis in reply.

## 📌 Features

- **Image analysis:** Describes photos, objects, people, and scenes.
- **Text extraction:** Reads visible text from screenshots, documents, signs, and handwritten notes.
- **Structured data:** Organizes information from tables into a clear format.
- **Arabic-friendly replies:** Responds in the language found in the image, or Arabic by default.
- **Telegram integration:** Sends the analysis back to the user in the same chat.

## 🛠️ Tech Stack

- **Automation Tool:** n8n
- **Messaging Platform:** Telegram Bot API
- **AI Model:** Google Gemini
- **Workflow Format:** JSON

## 🔧 Setup

1. Download `AI_TELE_PIC_redacted.json` from this repository.
2. Import the JSON workflow into n8n.
3. Connect your Telegram bot credentials and Google Gemini credentials.
4. Activate the workflow and send an image to your Telegram bot.

## 🔐 Credentials

Credentials are not included in the exported workflow. Add your own Telegram and Gemini connections in n8n before running it.
