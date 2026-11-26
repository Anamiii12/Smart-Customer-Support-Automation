# Smart-Customer-Support-Automation
Automated customer support ticket management using n8n and Google Sheets.
# Smart Customer Support Ticket Automation

## Overview
An automated customer support ticket management system built using n8n and Google Sheets. It receives customer queries through a production webhook, validates submitted information, processes support tickets, and stores them in Google Sheets.

## Features
- Webhook-based ticket submission
- Customer input validation
- Automated ticket processing
- Priority handling
- Google Sheets integration
- Production webhook testing

## Technologies Used
- n8n – Workflow automation
- Google Sheets – Ticket storage
- REST API – Webhook communication
- JSON – Data exchange
- PowerShell – API testing

## Workflow
1. Customer submits a support ticket.
2. The webhook receives the request.
3. Input fields are validated.
4. The workflow processes the ticket.
5. Ticket information is stored in Google Sheets.
6. A response is returned to the requester.

## Testing
Successfully tested using PowerShell and the production webhook. Verified that submitted tickets were added to Google Sheets.

## Project Structure
- `workflow.json` – Exported n8n workflow
- `README.md` – Project documentation

## Learning Outcomes
- Building automation workflows
- Working with REST APIs and webhooks
- JSON data handling
- Integrating Google Sheets with n8n
- Testing production workflows

## Author
B.Tech Computer Science and Engineering Student
