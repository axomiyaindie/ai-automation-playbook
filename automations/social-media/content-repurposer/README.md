# 🎬 Content Repurposer

Turn one long-form video/transcript into a week of social posts — threads, captions, hooks, and hashtags.

## What it does

1. Takes a YouTube URL, transcript, or uploaded text
2. Extracts key ideas with an LLM
3. Generates:
   - 5 X/Twitter posts
   - 3 LinkedIn posts
   - 5 Instagram captions + hashtags
   - 1 short-form video script
4. Saves output to Google Sheets / Notion (configurable)

## Prerequisites

- n8n (or adapt to Make/Zapier)
- OpenAI API key
- Optional: Google Sheets / Notion credentials

## Setup

1. Import `workflow.json`
2. Add your **OpenAI** credential
3. Add your **Google Sheets** (or Notion) credential
4. Edit the prompt node to match your voice/brand
5. Run it

## Cost

~$0.01–0.05 per run with `gpt-4o-mini`.

## Customize

- Change tone in the system prompt
- Add platforms by duplicating the final LLM node
- Swap output to email/Airtable/CSV
