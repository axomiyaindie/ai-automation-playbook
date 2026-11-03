# 📅 AI Appointment Setter

Auto-replies to booking inquiries, qualifies the lead with 2–3 questions, then offers available slots and creates the calendar event.

## What it does

1. New message/email/form → trigger
2. AI asks qualifying questions (budget, timeline, need)
3. Checks Google Calendar availability
4. Offers 2–3 slots, confirms, and creates the event
5. Sends confirmation email + adds to CRM

## Prerequisites

- n8n
- OpenAI API key
- Google Calendar OAuth
- Email (Gmail/SMTP) or Twilio/WhatsApp
- Optional: Cal.com / Calendly instead of raw Calendar

## Setup

1. Import `workflow.json`
2. Connect Google Calendar + email credentials
3. Edit the qualifying questions and brand voice
4. Set business hours in the Calendar node
5. Test with your own email first

## Tips

- Keep qualification short — 2–3 questions max
- Always allow a human handoff path
- Log every conversation to Sheets/CRM for audit
