# Getting Started

## 1. Pick a tool

- **n8n** — free & self-hostable. Start here: https://docs.n8n.io
  - Docker: `docker run -it --rm -p 5678:5678 n8nio/n8n`
  - Then open http://localhost:5678
- **Make** — https://make.com
- **Zapier** — https://zapier.com

Most workflows in this repo are exported as **n8n JSON** (most portable & free).

## 2. Get an OpenAI key

1. Go to https://platform.openai.com/api-keys
2. Create a key
3. Paste it into your tool's credentials (never commit it!)

## 3. Import a workflow (n8n example)

1. Open n8n → **Workflows** → **Import from file**
2. Select a `workflow.json` from an automation folder
3. Open each node and fill in credentials
4. Click **Execute workflow** to test
5. Toggle **Active** when ready

## 4. Keep secrets safe

Store keys in the tool's credential manager — **never** in the JSON or repo.
