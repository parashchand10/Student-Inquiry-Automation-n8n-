# Student-Inquiry-Automation-n8n
---
An automated workflow designed to streamline student inquiries, categorize requests using AI, and sync data across CRM and communication platforms. This project leverages n8n to eliminate manual data entry and ensure faster response times for prospective students.


Workflow Diagram
---
**AI Student Inquiry Automation Flow**

<img src="https://github.com/parashchand10/Student-Inquiry-Automation-n8n/blob/main/AI%20Automation%20Flow.png" height="1500" width="1000">

**Lead Scoring & Email Automation Flow**

<img src="Lead Automation.png" alt="n8n Project" width="800" height="800" />

Features
---
1. Multi-Channel Intake: Automatically captures inquiries from Webflow/Elementor forms, Email, and WhatsApp.
2. AI Categorization: Uses OpenAI/Anthropic to tag inquiries by urgency and interest level.
3. Lead Management: Syncs data directly to Google Sheets or CRMs (like HubSpot/Salesforce).
4. Instant Notifications: Sends real-time alerts to the admissions team via Slack or Discord.
5. Auto-Responder: Sends a personalized "Thank You" email to the student immediately.


Tech Stack
---
1. Automation: n8n.io
2. Storage: Google Sheets / PostgreSQL
3. Communication: Gmail API, Slack API
4. AI: OpenAI API (for sentiment analysis and tagging)


Installation & Setup
---
1. Self-hosted n8n: Ensure you have an active n8n instance running.
2. Import Workflow: * Download the student_inquiry_workflow.json from this repository.
3. In n8n, click on Workflows > Import from File.
Configure Credentials:
Set up your API keys for Google, OpenAI, and your chosen mail provider in the n8n Credentials section.
4. Activate: Toggle the workflow to Active to start receiving inquiries.
