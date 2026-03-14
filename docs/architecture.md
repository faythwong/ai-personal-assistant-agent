# System Architecture

This project implements an AI personal assistant capable of orchestrating multiple productivity tools through natural language instructions.

---

# Core Components

### 1. Chat Trigger

The workflow begins when a user sends a message through the assistant interface.

---

### 2. AI Agent

The agent interprets the request using an LLM.

It determines:

• user intent  
• required tools  
• parameters for execution

---

### 3. Memory Module

A conversation memory buffer maintains context from previous interactions.

This enables more natural conversations.

---

### 4. MCP Tool Router

The Model Context Protocol (MCP) allows the AI agent to interact with multiple connected tools.

---

# Connected Tools

### Gmail

Used for:

• drafting emails  
• retrieving recent messages

---

### Google Calendar

Used for:

• creating events  
• retrieving meetings  
• updating schedules

---

### Google Sheets

Used as a lightweight CRM database to store contacts.

Operations include:

• adding contacts  
• finding contacts  
• updating contact records

---

# Execution Flow

```
User Message
     │
     ▼
AI Agent
     │
     ▼
Intent Detection
     │
     ▼
Tool Selection
     │
 ┌───┼───────────┐
 │   │           │
 ▼   ▼           ▼
Email  Calendar  CRM
```

---

# Design Goals

• modular architecture  
• easy integration with additional tools  
• conversational natural language interface  
• scalable automation system
