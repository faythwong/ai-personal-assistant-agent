# AI Personal Assistant Agent

An AI-powered personal assistant built using **n8n**, **LLM tool-calling**, and **MCP (Model Context Protocol)** to automate everyday productivity tasks such as scheduling meetings, drafting emails, and managing contacts.

The assistant connects natural language commands with external services like **Gmail, Google Calendar, and Google Sheets**.

---

# Features

• Natural language assistant interface  
• Automated email drafting via Gmail  
• Meeting scheduling via Google Calendar  
• Contact management using Google Sheets  
• Multi-tool orchestration through MCP  
• Memory-enabled conversational agent  
• Easily extensible with additional services

---

# Example Capabilities

The assistant can understand requests like:

• "Schedule a meeting with John tomorrow at 3pm."  
• "Draft an email to Sarah explaining the project delay."  
• "Find the contact details for Michael."  
• "Show my meetings for tomorrow."  
• "Add a new contact to my CRM sheet."

---

# Workflow Overview

```
User Message
     │
     ▼
AI Agent (LLM)
     │
     ▼
Tool Selection
     │
 ┌───┼───────────┐
 │   │           │
 ▼   ▼           ▼
Gmail  Calendar  Google Sheets
 │       │         │
 ▼       ▼         ▼
Draft    Create    CRM
Email    Event     Update
```

---

# Tech Stack

• n8n  
• LLM (OpenAI / Gemini compatible)  
• Model Context Protocol (MCP)  
• Gmail API  
• Google Calendar API  
• Google Sheets API  

---

# Repository Structure

```
ai-personal-assistant-agent
│
├── README.md
├── workflow
│   └── personal-assistant-agent.json
├── docs
│   ├── architecture.md
│   ├── setup-guide.md
│   └── example-commands.md
├── demo
│   └── demo-scenarios.md
└── LICENSE
```

---

# Setup

See the detailed guide:

docs/setup-guide.md

---

# Documentation

• System Architecture → docs/architecture.md  
• Setup Guide → docs/setup-guide.md  
• Example Commands → docs/example-commands.md  
• Demo Scenarios → demo/demo-scenarios.md  

---

# Security Notice

All credentials, API keys, tokens, endpoints, and personal identifiers have been removed from this repository.

---

# Skills Demonstrated

• AI agent orchestration  
• tool-calling LLM architecture  
• workflow automation  
• API integrations  
• conversational AI systems  
• automation engineering

---

# License

MIT License
