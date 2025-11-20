# Email Assistant – n8n + Google Gemini

An intelligent email automation workflow built with **n8n** and **Google Gemini** that can:

- Classify incoming emails (for example: important, spam, info, follow-up)
- Summarize email content
- Generate context-aware reply drafts
- Log activity in **Google Sheets**
- Automatically reply or route emails based on category

The core of this project is an exported n8n workflow (`Email_Assistant.json`) that you can import into your own n8n instance.

---

## ✨ Features

- **Automatic email classification**  
  Uses Google Gemini to decide what type of email it is (e.g. “Reply”, “Ignore”, “Info only”, “Forward to team”, etc.).

- **Smart summaries**  
  Generates short, readable summaries of long or complex emails.

- **AI-generated replies**  
  Drafts clear, professional replies based on the email content and your prompt instructions.

- **Gmail integration**  
  Reads incoming emails and sends replies using your Gmail account (via Gmail API / n8n credentials).

- **Google Sheets logging**  
  Stores email metadata, classification, summary, and action taken in a Google Sheet for tracking.

- **Configurable logic in n8n**  
  You can adjust categories, prompts, routing logic, and thresholds directly inside the workflow.

---

## 🧩 Tech Stack

- **n8n** – Workflow automation platform  
- **Google Gemini** – LLM for classification, summarization, and reply generation  
- **Gmail API** – For reading and sending emails  
- **Google Sheets API** – For logging email activity  



