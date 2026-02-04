
# Resume-Driven Job Automation (n8n)

This project is an end-to-end AI automation built using n8n.

It takes a resume PDF as input, parses it using an LLM, fetches live job listings from Naukri, and sends personalized job matches via email.

## Tech Stack
- n8n
- JavaScript
- LLM APIs (OpenRouter / OpenAI-compatible)
- Apify
- Google Drive API
- Gmail API

## How It Works
1. Upload resume PDF to Google Drive
2. Resume is parsed and structured using AI
3. Primary role is extracted programmatically
4. Live jobs are fetched from Naukri
5. One consolidated email is sent to the user

## Credentials Setup (Required)

This workflow does NOT include credentials.

Before running:
- Create Google Drive OAuth credential in n8n
- Create Google Sheets OAuth credential
- Create Gmail OAuth credential
- Add OpenRouter API key
- Add Apify API token

Replace placeholders:
- {{OPENROUTER_API_KEY}}
- {{APIFY_API_TOKEN}}

No secrets are stored in this repository.


⚠️ API keys are not included. Configure credentials inside n8n.

