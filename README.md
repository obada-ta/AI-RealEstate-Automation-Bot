# 🏢 AI Real Estate Lead Qualification & Automation System

An automated lead qualification system built with n8n, OpenAI, and Telegram Bot API. It captures incoming real estate inquiries, uses AI agents to qualify buyer preferences, and routes structured leads directly to CRM pipelines.

---

## 📹 Video Demo
Watch a short 2-minute walkthrough of the system in action:
👉 [Watch the Live Demo Here](ضع_رابط_الفيديو_هنا)

---

## 🌟 Key Features
- Automated Ingestion: Instant processing of Telegram inquiries via n8n Webhooks.
- AI Qualification: Uses custom prompts to extract budget, location, property type, and buyer intent.
- CRM & Pipeline Routing: Automatically categorizes and pushes qualified leads to the appropriate sales pipeline.

## 🛠 Tech Stack
- Workflow Automation: n8n
- AI Engine: OpenAI API (GPT Models)
- Messaging: Telegram Bot API
- Data Integration: Webhooks / HTTP Requests / JSON Parsing

## 🚀 How to Import
1. Download the real_estate_lead_qualification.json file from the n8n_workflows/ folder.
2. Open your n8n instance and click Import from File.
3. Configure your API credentials using the structure shown in .env.example.
