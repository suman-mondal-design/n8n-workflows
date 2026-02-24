# n8n Workflows 🤖

This repository contains my **n8n automation workflows**, including AI-powered Telegram bots and business automation tools.

## 📌 Overview

These workflows are built using **n8n**, an open-source workflow automation platform. They integrate with services like:

* Telegram Bot API
* Google Gemini AI
* Webhooks (ngrok / public endpoints)
* Custom business automation tools

The goal is to automate communication, AI responses, and business processes.

---

## 🚀 Current Workflow: Telegram AI Assistant

### Features

* Receives messages from Telegram users
* Sends messages to Google Gemini AI
* Generates intelligent responses
* Sends replies back to Telegram automatically

### Workflow File

```
My workflow (Feb 17 at 14_59_33) (1).json
```

---

## 🛠 Requirements

* Node.js (v18+ recommended)
* n8n installed globally

```
npm install -g n8n
```

* ngrok (for webhook access)
* Telegram Bot Token
* Google Gemini API Key

---

## ▶️ How to Use

### 1. Start n8n

```
n8n start
```

### 2. Import workflow

* Open http://localhost:5678
* Click **Import workflow**
* Select the JSON file

### 3. Configure credentials

Add:

* Telegram Bot Token
* Gemini API Key

### 4. Activate workflow

Turn ON the workflow toggle.

---

## 🌐 Webhook Setup (ngrok example)

```
ngrok http 5678
```

Set environment variable:

```
set WEBHOOK_URL=https://your-ngrok-url.ngrok-free.dev
```

---

## 📂 Repository Structure

```
.
├── README.md
├── My workflow (Feb 17 at 14_59_33) (1).json
```

---

## 🎯 Use Cases

* AI Telegram bots
* Customer support automation
* Business workflow automation
* AI assistants for companies

---

## 👤 Author

**Suman Mondal**
GitHub: https://github.com/suman-mondal-design

---

## 📜 License

This project is open-source and available under the MIT License.
