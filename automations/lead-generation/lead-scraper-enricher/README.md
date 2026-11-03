# 🎯 Lead Scraper & Enricher

Find leads that match your ICP, enrich them with public info, and score them with AI — then push to your CRM/Sheets.

## What it does

1. Reads target criteria (niche, location, role) from a config
2. Pulls candidate leads from a source (Apollo, Google Maps, LinkedIn via API, or a CSV)
3. Enriches each with company size / website / recent news
4. Uses an LLM to **score fit 1–10** and write a 1-line personalized opener
5. Saves to Google Sheets / HubSpot / Airtable

## Prerequisites

- n8n
- OpenAI API key
- One lead source API (Apollo, PhantomBuster, SerpAPI, or a CSV)
- Google Sheets or CRM credentials

## Setup

1. Import `workflow.json`
2. Fill credentials
3. Edit the ICP prompt in the scoring node
4. Run on a small batch first

## ⚠️ Ethics & compliance

- Respect each source's ToS and robots.txt
- Follow GDPR/CAN-SPAM — don't scrape personal data without a lawful basis
- The AI opener is a draft — review before sending
