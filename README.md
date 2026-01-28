# AI-Powered Attendance Bot 🤖
An advanced, state-aware attendance tracking system that automates employee check-ins and check-outs using n8n, Telegram, and Google Sheets, with Gemini AI handling natural language processing.


## 🚀 Overview
This system eliminates the need for manual logs or rigid command-based bots. Employees simply message the Telegram bot in natural language, and the system intelligently determines their status by cross-referencing live data in Google Sheets.

## 🛠️ Tech Stack
Workflow Engine: n8n

Artificial Intelligence: Google Gemini API

Communication: Telegram Bot API

Database: Google Sheets

## ✨ Key Features
Automated State Detection: The bot automatically queries the Google Sheet to determine if an employee is checking in or out based on their last recorded entry.

Natural Language Processing: Powered by Gemini AI, the bot understands context and intent, allowing employees to talk naturally (e.g., "Starting my shift" or "Heading home").

Real-Time Data Sync: Instant updates to the master attendance sheet, ensuring HR has access to live data.

Error Handling: Built-in logic to prevent double check-ins or checking out without a prior check-in.

## 📋 Prerequisites
Before running this project, you will need:

An n8n instance (Desktop or Cloud)

A Telegram Bot Token from @BotFather

A Google Gemini API Key

A Google Cloud Service Account for Google Sheets access

## 🔧 Setup Instructions
Clone the Repository: git clone https://github.com/iamansh-alt/ai-attendance-bot.git

Import Workflow: Import the .json file from the /workflows folder into your n8n instance.

Set Environment Variables: Add your API keys and credentials to your n8n credentials manager. Do not upload your real .env or credentials.json files.

Connect Google Sheet: Link the workflow to your specific Google Sheet ID.

📄 License
This project is licensed under the MIT License—feel free to use it for your own business or personal projects.
