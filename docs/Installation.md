# ⚙ Installation Guide

## Prerequisites

- n8n
- Groq API Key
- Google Account
- Google Sheets
- Gmail Credentials

---

## Clone Repository

```bash
git clone https://github.com/yourusername/telecom-noc-copilot.git
```

---

## Configure n8n

Import

```
workflow/telecom-noc-copilot.json
```

---

## Configure Credentials

### Groq

Add

- API Key

---

### Google Sheets

Authenticate Google Account.

---

### Gmail

Configure SMTP or Gmail OAuth.

---

## Execute

Trigger the webhook with telecom alarm data.

The workflow automatically

- analyzes incident
- generates RCA
- classifies severity
- stores results

---