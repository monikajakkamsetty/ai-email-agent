
# AI Email Agent 🤖📧

An intelligent email automation system that automatically 
reads, classifies, and replies to emails using AI.

## Features
- 📧 Automatically reads incoming Gmail emails
- 🤖 AI-powered reply generation using Google Gemini
- 📝 Classifies emails (Inquiry, Complaint, Spam, General)
- ✅ Sends professional replies automatically
- 🧠 Memory/context aware per email thread

## Tech Stack
- n8n (Workflow Automation)
- Google Gemini AI (LLM)
- Gmail API (OAuth2)

## Workflow
Gmail Trigger → Read Content → AI Agent → Clean Output → Write Reply → Send Reply
https://github.com/monikajakkamsetty/ai-email-agent/blob/main/Screenshot%202026-05-21%20121136.png

## Setup
1. Import the workflow JSON into n8n
2. Add Gmail OAuth2 credentials
3. Add Google Gemini API key
4. Activate the workflow

## Author
Monika Jakkamsetty
