---
title: career_conversations
app_file: app.py
sdk: gradio
sdk_version: 5.34.2
---

# Career Conversations AI Bot

This project is an AI-powered chatbot that allows users to interactively chat with Robin Newhouse's LinkedIn profile and resume. The bot is designed to answer questions about Robin's career, background, skills, and experience, providing professional and engaging responses as if Robin himself were responding.

**This project is modified from Ed Donner's course on Agentic AI Engineering. For more information, see the original course here: [The Complete Agentic AI Engineering Course](https://edwarddonner.com/2025/04/21/the-complete-agentic-ai-engineering-course/).**

## Features
- Chat with an AI that represents Robin Newhouse
- Ask questions about Robin's career, background, and skills
- The AI uses Robin's LinkedIn profile and resume to answer questions
- If the AI cannot answer a question, it records it for review
- Encourages users to get in touch via email for further conversation

## How it works
The bot loads Robin's LinkedIn profile (from PDF) and a summary (from text) and uses OpenAI's GPT models to generate responses. It is accessible via a web interface built with Gradio.

## Getting Started
1. Clone the repository
2. Install dependencies from `requirements.txt`
3. Add your environment variables (see `.env.example`)
4. Run the app with `python app.py`

## License
MIT
