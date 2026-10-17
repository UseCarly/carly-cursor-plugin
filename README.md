# Carly

Plugin that connects agents to [Carly](https://carlyassistant.com), the AI assistant for email, calendar, CRM, and workflows.

Carly holds all of your Gmail and Outlook accounts at once and connects to thousands of apps, so one agent can read and send mail, schedule across every calendar, update your CRM, and run workflows that fire the moment an email arrives or a meeting is booked.

## Install

**Grok Bot:** open **Connect apps** in the sidebar, find **Carly**, and choose **Add**. Sign in to Carly when the card appears.

**Cursor:** open **Cursor Settings → Plugins**, search for **Carly**, and click **Install**. Or run `/add-plugin carly` in chat.

Then connect your accounts and apps at [carlyassistant.com/integrations](https://carlyassistant.com/integrations).

## MCP

```json
{
  "mcpServers": {
    "carly": {
      "type": "http",
      "url": "https://carlyassistant.com/mcp"
    }
  }
}
```

Auth is OAuth 2.1 with PKCE. Every connection is bound to one person's Carly account, and there is no API key to paste.

## What agents can do

| Category | Capabilities |
| --- | --- |
| Email | Search and read mail across every connected mailbox; send and reply; draft, label, move, flag, unsubscribe |
| Calendar | Find free time across all calendars; create, move, and cancel events; run group scheduling polls |
| Contacts and CRM | Look up people; search, query, and update CRM records |
| Workflows | Build workflows in plain English or start from a template; test, run, pause, and schedule them |
| Files | Google Drive and OneDrive: list, download, share, create folders and Docs |
| Booking pages | Create and update booking pages; list slots and bookings |
| Apps | Work in thousands of connected apps through one connection |

Read-only tools run without interrupting you. Tools that write ask first.

## Pricing

Free Zapier-style workflows; AI agents from $35/month.

## Support

[usecarly.com/mcp](https://www.usecarly.com/mcp/) lists every tool. Questions: support@calbotservice.com
