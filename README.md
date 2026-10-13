# 📄 Document Tools Skill

Create/edit Word, PDF, PPTX, XLSX - document parsing and productivity

**Repository by:** [Alpesh Makwana](https://github.com/makwanaalpesh811-a11y)

---

## 📦 What's Inside

9 Hermes Agent skills for document tools skill:

- `document-to-action-items` — "Extract cited obligations, deadlines, tasks from documents."
- `docx` — Create, read, edit, template, and review Word .docx files.
- `excel-author` — Build auditable financial workbooks headless via openpyxl.
- `meeting-action-items` — "Turn meeting notes into cited decisions, owners, tickets."
- `pdf` — "PDF files: create, read, merge, fill, OCR, edit text."
- `pdf-read-ocr` — Read PDFs on Termux with OCR fallback for scanned docs.
---

# PDF Read & OCR (Termux Android)

R...
- `powerpoint` — Create, read, edit .pptx decks with python-pptx.
- `teams-meeting-pipeline` — Teams meeting summaries, job replay, Graph subscriptions.
- `xlsx` — Create, read, edit Excel .xlsx workbooks and CSVs.

---


## 🔐 SECURITY NOTICE

**This repo is safe to use publicly.** It contains only skill definitions (SKILL.md) and documentation - no live credentials.

### What NOT to commit:
- API keys (GitHub, YouTube, Gemini, OpenAI, etc.)
- AWS credentials (`~/.aws/credentials`)
- Telegram bot tokens
- Exchange API keys (Delta, Hyperliquid, etc.)
- Private keys or certificates

### Where to store secrets (on your machine):
```
~/.aws/credentials          # AWS
~/.youtube_token.json       # YouTube OAuth
~/.ig_env                   # Instagram/Gemini
~/.signal_bot_env           # Trading bot
~/.gh_token                 # GitHub token
```

All skills are designed to read secrets from your filesystem, not embed them.


## 🚀 Installation

### Option 1: Clone to Hermes skills directory
```bash
git clone https://github.com/makwanaalpesh811-a11y/document-tools-skill.git ~/.hermes/skills/document-tools-skill
```

### Option 2: Install individual skills
```bash
# Create skills dir if not exists
mkdir -p ~/.hermes/skills

# Clone only what you need
git clone --depth 1 --filter=blob:none https://github.com/makwanaalpesh811-a11y/document-tools-skill.git /tmp/document-tools-skill
cp -r /tmp/document-tools-skill/skills/* ~/.hermes/skills/
```

---

## ⚙️ Prerequisites

Check each skill's `SKILL.md` for specific dependencies. Common ones:
- **Termux** (Android terminal) or Linux/macOS
- **Python 3.11+**
- **Node.js + npm** (for CLI-based skills)
- **API keys** stored in `~/.<name>_env` or `~/.<name>_token.json` files

---

## 🔧 Setup Guide

1. **Install Hermes Agent:** `pip install hermes-agent` or see [Hermes docs](https://hermes-agent.nousresearch.com/docs)
2. **Clone this repo** into `~/.hermes/skills/`
3. **Configure credentials** in your environment (see each skill's SKILL.md)
4. **Use in chat:** Ask Hermes to use any skill by name

---

## 📚 Skill Documentation

Each skill lives in `skills/<skill-name>/SKILL.md` with:
- **YAML frontmatter:** name, description
- **Commands:** CLI/API references
- **Examples:** Ready-to-use snippets
- **Gotchas:** Real-world pitfalls

---

## 🛡️ Security

## 🔐 SECURITY NOTICE

**This repo is safe to use publicly.** It contains only skill definitions (SKILL.md) and documentation - no live credentials.

### What NOT to commit:
- API keys (GitHub, YouTube, Gemini, OpenAI, etc.)
- AWS credentials (`~/.aws/credentials`)
- Telegram bot tokens
- Exchange API keys (Delta, Hyperliquid, etc.)
- Private keys or certificates

### Where to store secrets (on your machine):
```
~/.aws/credentials          # AWS
~/.youtube_token.json       # YouTube OAuth
~/.ig_env                   # Instagram/Gemini
~/.signal_bot_env           # Trading bot
~/.gh_token                 # GitHub token
```

All skills are designed to read secrets from your filesystem, not embed them.

---

## 📜 License

MIT License - see [LICENSE](./LICENSE)

---

## 👨‍💻 Author

**Alpesh Makwana** — Trading, content, and Hermes Agent enthusiast.

- **GitHub:** [makwanaalpesh811-a11y](https://github.com/makwanaalpesh811-a11y)
- **Telegram:** @alpeshalgobot

---

## 🤝 Contributing

Issues and PRs welcome. Follow the SKILL.md format conventions.

## 🏷️ Topics
`documents` `docx` `pdf` `xlsx` `powerpoint` 
