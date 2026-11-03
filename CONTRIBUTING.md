# Contributing

Thanks for adding to the playbook! 🙌

## Adding an automation

1. Fork the repo
2. Create `automations/<category>/<automation-name>/`
3. Add:
   - `README.md` (copy `templates/automation-template.md`)
   - `workflow.json` (export from your tool, **no secrets**)
   - optional `assets/` for screenshots
4. Update the table in the root `README.md`
5. Open a PR with a short description + demo screenshot

## Rules

- **Never commit API keys** or personal data
- Keep workflows as portable as possible (n8n preferred)
- Document cost & compliance
- One automation per PR
