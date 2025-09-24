# helpdesk-ticketing-simulation

**Project overview**  
A small helpdesk / IT support simulation using Jira Service Management (Free) plus a public Knowledge Base in Markdown. This repository demonstrates typical ticket workflows, documentation practices, and example KB articles for common user issues.

**Tools used**
- Jira Service Management (Free) — ticketing & queues
- Confluence (optional) — linked knowledge base
- GitHub — project repository and KB hosting
- Local tools used for testing: Windows 10/11 VM, VirtualBox, basic networking commands

## Sample workflow (ticket → resolution → documentation)
1. **Ticket created** (user/employee via Jira portal) — e.g., "Wi-Fi not connecting".
2. **Triage** (support agent) — gather logs and reproduce issue.
3. **Troubleshoot & resolve** — apply fix (commands, config, driver update).
4. **Document** — create or update KB article, attach screenshots and steps.
5. **Close ticket** — add link to KB article in ticket resolution notes.

## What’s in this repo
- `README.md` — project overview and usage
- `/knowledge_base/` — Markdown KB articles (Wi-Fi, Printer, Password Reset)
- `/screenshots/` — screenshots of Jira tickets, KB pages, and troubleshooting steps (place your images here)
- `.gitignore` — recommended ignore entries

## How to use
1. Browse the KB articles in `/knowledge_base/` or publish them to GitHub Pages / mkdocs for a nicer view.
2. Link KB article URLs in your Jira Service Management ticket resolutions.
3. Add screenshots to `/screenshots/` and reference them in KB articles.

## What to commit to this repo
- Finalized KB `.md` articles
- Small screenshots (cropped and optimized)
- `README.md` and documentation
- Example ticket text / resolution notes (sanitized — no real PII or passwords)


---

