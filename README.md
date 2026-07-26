# AI Ticket Router

## Overview

This project automates customer support ticket routing using n8n and Google Gemini AI.

It analyzes incoming support tickets, identifies their category using AI, and routes them to the appropriate support team based on predefined business rules.

---

## Business Problem

Support teams often receive a large number of customer requests from different channels. Manually identifying the correct department for each ticket is time-consuming and can delay response times.

This workflow automates ticket routing using AI, reducing manual effort and improving operational efficiency.

---

## Solution

The workflow receives incoming support tickets, processes the request, uses Google Gemini AI to determine the ticket category, and automatically routes the ticket to the appropriate destination.

---

## Workflow

Webhook

↓

Edit Fields

↓

Google Gemini AI

↓

Route Ticket

↓

Return Response

---

## Features

- AI-powered ticket classification
- Automatic ticket routing
- Google Gemini AI integration
- Business rule-based automation
- Real-time workflow execution
- REST API support
- Beginner-friendly and easy to customize

---

## Technologies Used

- n8n
- Google Gemini AI
- REST API
- JSON
- Webhooks

---

## Project Structure

```text
README.md
LICENSE
Project-03-AI-Ticket-Router.json
```

---

## How to Import

1. Download the workflow JSON file.
2. Open n8n.
3. Click **Import Workflow**.
4. Select `Project-03-AI-Ticket-Router.json`.
5. Configure your Google Gemini AI credentials.
6. Execute the workflow.

---

## Sample Input

```json
{
  "customerName": "John",
  "issue": "Unable to process payment"
}
```

---

## Sample Output

```json
{
  "category": "Billing",
  "route": "Billing Support Team"
}
```

---

## Use Cases

- Customer Support Automation
- AI Ticket Routing
- CRM Automation
- Helpdesk Systems
- Workflow Automation
- AI Operations

---

## Future Improvements

- Priority prediction
- Sentiment analysis
- Automatic SLA assignment
- CRM integration
- Slack or Microsoft Teams notifications
- Multi-language ticket routing

---

## Project Status

Completed

---

## Author

**Buddha Dorababu**

AI Automation Engineer | n8n | AI Workflows | Gemini AI | CRM Automation | API Integrations
