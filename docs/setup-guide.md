# Setup Guide

Follow these steps to deploy the AI Personal Assistant workflow.

---

# 1 Install n8n

Install globally:

```
npm install n8n -g
```

Or run with Docker.

---

# 2 Import Workflow

Open n8n.

Import:

```
workflow/personal-assistant-agent.json
```

---

# 3 Configure Credentials

Create credentials for:

• Gmail  
• Google Calendar  
• Google Sheets  
• OpenAI / Gemini API  

---

# 4 Configure MCP Server

Update the MCP endpoint placeholder with your MCP server URL.

Example:

```
MCP_SERVER_ENDPOINT
```

---

# 5 Replace Placeholder IDs

Update these placeholders:

• GOOGLE_SHEETS_DOCUMENT_ID  
• CALENDAR_ID  
• MCP_SERVER_ENDPOINT  

---

# 6 Activate Workflow

Once credentials are configured:

Enable the workflow.

The assistant can now respond to chat commands.

---

# Optional Extensions

You can extend the assistant with:

• Slack  
• Notion  
• CRM systems  
• project management tools
