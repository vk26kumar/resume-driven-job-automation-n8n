# resume-driven-job-automation-n8n
An end-to-end resume-driven AI automation built with n8n that parses resumes, fetches live jobs, and sends personalized job matches via email.

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

⚠️ API keys are not included. Configure credentials inside n8n.

