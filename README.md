# FinGuide AI — Financial Planning Agent

FinGuide AI is a text-based financial planning assistant built using n8n, OpenAI, and Google Sheets.

## Project Overview

FinGuide helps users understand their spending, manage a monthly budget, and work toward financial goals.

## Main Features

- **AI Financial Assistant:** Answers questions about budgeting, savings, and basic investment concepts.
- **Expense Tracking:** Reads and records transactions in Google Sheets.
- **Budget Planning:** Helps users compare spending against their planned budget.
- **Financial Calculations:** Calculates expenses and savings targets.
- **Conversation Memory:** Remembers previous messages within a chat session.

## How the Workflow Works

1. A user sends a message through the n8n Chat Trigger.
2. The AI Agent understands the question.
3. The agent uses Google Sheets or Calculator tools when needed.
4. The AI returns a written financial explanation or suggested action.

## Technologies

- n8n — workflow automation
- OpenAI GPT-4o-mini — AI model
- Google Sheets — financial records
- Calculator — financial calculations

## Workflow File

[Download the FinGuide AI n8n Workflow](./FinGuide-AI-Workflow.json)

Import the JSON file into n8n and configure your own API credentials and Google Sheets document before testing.

## Future Improvements

- Savings goal tracking
- Excel workbook export
- Financial dashboard and charts
- Stronger approval controls for editing transactions
- Investment scenario planning

## Important Note

FinGuide is an educational financial planning prototype. It does not execute investments or provide guaranteed financial returns. Use fictional financial data when testing the public demonstration.
