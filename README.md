# 🤖 AI Project Manager Agent

An AI-powered personal assistant built with **n8n** that helps users manage emails, calendar events, web searches, and Airtable records through natural language conversations.

## ✨ Features

- **📧 Email Management:** Retrieve recent emails and help users find relevant email information through Gmail.
- **📅 Calendar Management:** Check calendar events and create new events using Google Calendar.
- **🔎 Web Search:** Search Google for external information using SerpAPI.
- **🗂️ Airtable Integration:** Connect with Airtable to retrieve records from a data workspace.
- **🧠 Conversational Memory:** Maintain conversation context using n8n's Simple Memory node.
- **💬 AI Chat Interface:** Interact with the assistant using natural language.
- **🤖 AI-Powered Responses:** Use an OpenRouter chat model to understand requests and coordinate available tools.

## 🛠️ Tech Stack

- [n8n](https://n8n.io/) — Workflow automation
- OpenRouter — AI language model integration
- Gmail API — Email management
- Google Calendar API — Calendar operations
- Airtable API — Data retrieval
- SerpAPI — Google search integration

## ⚙️ Workflow Overview

1. The user sends a message through the n8n chat interface.
2. The AI agent interprets the request.
3. The agent selects the appropriate connected tool.
4. The requested information or action is processed through the relevant service.
5. The agent returns a natural-language response to the user.

## 🚀 Setup

1. Import the `Project Manager Agent.json` workflow into your n8n instance.
2. Configure your OpenRouter credentials.
3. Connect your Gmail account.
4. Connect your Google Calendar account.
5. Configure your Airtable credentials and select the appropriate base and table.
6. Configure your SerpAPI credentials.
7. Review each node's settings and permissions.
8. Test the workflow before using it.

## 🔐 Requirements

- A running n8n instance.
- An OpenRouter account and API access.
- Authorized Gmail and Google Calendar accounts.
- An Airtable account with access to the required base and table.
- A SerpAPI account and API access.

Some services may require enabling their APIs and completing OAuth authorization.

## ⚠️ Important Notes

- Credentials must be configured in n8n before the workflow can operate.
- Review node parameters and permissions before running the workflow.
- Test email and calendar operations carefully.
- The workflow configuration may require adjustments to match your accounts and data.
- Never publish API keys, access tokens, passwords, or other sensitive information.

## 🔮 Future Improvements

- Advanced email search and message retrieval.
- Improved calendar conflict detection.
- More comprehensive Airtable search and record management.
- Better error handling and validation.
- Additional integrations and automation capabilities.

## 👨‍💻 Author

**Ahmed Ahmed Abass Fouda**

AI Automation Developer | n8n & AI Agents

---

*Built with n8n to explore practical AI agents and workflow automation.*
