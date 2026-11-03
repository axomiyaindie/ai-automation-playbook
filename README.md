# 🧠 AI Automation Playbook

> A collection of practical, open-source **AI-powered automations** for social media, lead generation, bookings, and anything else that can be automated.

Each automation is self-contained: a short guide + a ready-to-import workflow file. Copy it, tweak it, ship it.

---

## 🚀 What's inside

| Category | Automation | Stack | Status |
|----------|------------|-------|--------|
| Social Media | [Content Repurposer](automations/social-media/content-repurposer/) | n8n + OpenAI | ✅ Ready |
| Lead Generation | [Lead Scraper & Enricher](automations/lead-generation/lead-scraper-enricher/) | n8n + OpenAI | ✅ Ready |
| Bookings | [AI Appointment Setter](automations/bookings/ai-appointment-setter/) | n8n + OpenAI | ✅ Ready |

More coming: cold outreach, content scheduling, review monitoring, invoice chasing, inbox triage…

---

## 🧩 How to use an automation

1. Open the automation folder you want.
2. Read its `README.md` — it lists prerequisites and setup steps.
3. Import the `workflow.json` into your tool (n8n, Make, Zapier, etc.).
4. Add your API keys and customize.
5. Run it. 🎉

See [docs/getting-started.md](docs/getting-started.md) for tool setup.

---

## 🛠 Supported tools

- **n8n** (self-hosted, free) — recommended
- **Make** / **Zapier**
- **OpenAI API** (GPT-4o / GPT-4o-mini)
- Anything else you can script (Python, Node, shell)

---

## 🤝 Contributing

Got an automation that saves you time? Open a PR! See [CONTRIBUTING.md](CONTRIBUTING.md) and use [templates/automation-template.md](templates/automation-template.md).

---

## 📜 License

MIT — use it, fork it, sell with it.
