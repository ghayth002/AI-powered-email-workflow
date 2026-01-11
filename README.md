# AI-Powered Email Automation System

## Overview
This project is an automated email generation and delivery system built using **n8n** and **AI language models**.  
It receives user input via a webhook, generates a customized email using AI, and sends it automatically via email.

## Features
- AI-generated email content
- Customizable tone, language, and length
- Webhook-based input handling
- Automated email sending (Gmail / SMTP)
- Workflow automation using n8n
- Prompt engineering to control output quality

## Tech Stack
- n8n (Workflow Automation)
- AI Language Model (LLM)
- Webhooks
- SMTP / Gmail / Outlook
- JSON-based workflow design

## Workflow Overview
1. User submits data via webhook (name, email, message)
2. Workflow processes and validates input
3. AI model generates email content
4. Email is sent automatically to the recipient

## Files
- `ai-email-automation-n8n.json` → Exported n8n workflow

## Use Cases
- Automated contact form replies
- AI-powered customer support responses
- Personalized email notifications
- Smart autoresponders

## Notes
Sensitive data such as API keys and credentials are not included in this repository.

## Author
Ghaith Oueslati
