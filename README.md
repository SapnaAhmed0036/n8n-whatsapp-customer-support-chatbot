## Project Description

This project is an AI-powered WhatsApp customer support chatbot implemented using **n8n** workflow automation.  
The chatbot automates end-to-end customer service operations by integrating **Twilio WhatsApp API** for messaging and **Airtable** as a lightweight backend for inventory management, order tracking, and support ticket handling.

The system is designed to provide fast, accurate, and professional customer responses while reducing manual support workload.

### Core Capabilities
- Automated WhatsApp customer support
- FAQ handling using structured logic
- Real-time order tracking via Airtable records
- Product availability and inventory lookup from Airtable
- Support ticket creation and assignment using Airtable
- Human-like conversational flow with validation and error handling
- 24/7 operation with scalable workflow design

### Technical Architecture
- Incoming WhatsApp messages are received via Twilio webhooks
- n8n processes messages and identifies user intent
- Airtable is queried for inventory, orders, and ticket data
- Responses are dynamically generated and sent back to WhatsApp
- Unresolved issues are escalated through ticket creation workflows

### Tech Stack
- n8n (Workflow Automation)
- Twilio WhatsApp API
- Airtable (Inventory, Orders, Ticketing)
- Webhooks & REST APIs
- JSON-based workflow design

### Use Cases
- Check product availability
- Track order status
- Handle customer FAQs
- Log and escalate customer support requests
- Maintain structured records without a traditional database

### Notes
- All credentials, API keys, and sensitive data have been removed
- Sample payloads are included for demonstration purposes
- This repository is intended for portfolio and educational use
