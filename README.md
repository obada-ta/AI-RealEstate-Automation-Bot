# 🏢 AI-Driven Real Estate Telegram Bot & Lead Routing Automation

An end-to-end automated system that acts as a real estate AI assistant over Telegram. It processes incoming user inquiries, uses AI (LLMs) to qualify property requirements, and automatically routes structured lead data to CRM pipelines via n8n workflows.

## 🌟 Key Features
- Instant Telegram Interaction: Captures prospective buyer/renter inquiries in real-time.
- AI Intent & Qualification Engine: Parses raw conversational input into structured JSON (Budget, Location, Property Type, Urgency).
- Automated CRM & Pipeline Routing: Uses n8n webhooks to automatically insert or update qualified leads in the appropriate sales pipeline stage.
- Smart Error Handling: Fallback mechanisms to handle ambiguous user responses gracefully.

## 🛠 Tech Stack & Architecture
- Workflow Automation: n8n (Webhooks, HTTP Requests, AI Agent Nodes)
- AI / LLM: OpenAI / Custom Prompt Engine for Structured Lead Scoring
- Messaging API: Telegram Bot API
- Backend / Data: Node.js / SQL / Webhooks

## ⚙️ How It Works
1. Trigger: User sends an inquiry to the Telegram Bot.
2. Webhooks Ingestion: Telegram forwards payload to an n8n webhook.
3. AI Qualification: The AI evaluates budget, preferences, and qualification rules.
4. Data Structuring: Outputs formatted JSON data.
5. CRM Dispatch: n8n routes high-priority leads to sales agents and updates CRM records automatically.
