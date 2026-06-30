# AI-Based Chatbot for IT Customer Service

## Project Overview
An AI-powered chatbot built using **Google Dialogflow ES** to automate routine IT support and customer service queries. This project was developed as part of the Master of Computer Application (MCA) program at Chandigarh University, under an internship engagement with Qollabb.

## Problem Statement
IT support teams handle a high volume of repetitive queries daily — password resets, VPN issues, account access, device troubleshooting — that consume time which could be spent on complex problems. This chatbot automates the first layer of IT support using Natural Language Processing.

## Technology Used
- **Platform:** Google Dialogflow ES
- **NLP Engine:** Google Cloud Natural Language Processing
- **Methodology:** Agile (iterative development)

## Intents Implemented
- `Default Welcome Intent` — Session greeting
- `Default Fallback Intent` — Graceful handling of unrecognised input
- `password.reset` — Password reset assistance
- `account.locked` — Locked account handling
- `vpn.troubleshoot` — Multi-turn VPN troubleshooting flow (with `vpn.troubleshoot - os` and `vpn.troubleshoot - error` follow-ups, plus yes/no resolution branches)
- `software.installation` — Software installation guidance
- `email.not.working` — Email issue troubleshooting
- `internet.not.working` — Internet connectivity issue handling
- `device.not.working` — Hardware/device issue triage
- `slow.performance` — Slow system performance troubleshooting
- `new.account.request` — New account setup requests
- `ticket.status` — Ticket status check (with yes/no follow-ups)
- `billing.inquiry` — Billing related queries
- `IT.contact.info` — IT department contact information
- `human.agent.request` — Escalation to a human agent
- `help` — General help/menu intent
- `ask.call` — Request a callback
- `ask.health` — Bot health/status check
- `goodbye` — Session closing

## Multi-Turn Conversation Example (VPN Troubleshooting)
## Repository Contents
- `IT_Support_Bot.zip` — Complete Dialogflow agent export containing all intents, training phrases, and responses in JSON format

## How to Use This Agent
1. Go to [Dialogflow ES Console](https://dialogflow.cloud.google.com)
2. Create a new agent
3. Go to Settings (gear icon) → Export and Import → Restore from ZIP
4. Upload `IT_Support_Bot.zip` from this repository
5. Test the agent using the "Try it now" panel

## Project Details
| Field | Value |
|---|---|
| Student | Burhan Gani Dar |
| Enrollment No | O24MCA111093 |
| Program | MCA, Chandigarh University |
| Mentor | Mr. Vikas Kumar Atray, Project Manager, Imarticus Learning |
| Internship Platform | Qollabb |
