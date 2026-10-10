# ✊ GushKhor *(ঘুষখোর)*

![Status](https://img.shields.io/badge/status-live-brightgreen)
![Language](https://img.shields.io/badge/UI-Bengali-red)
![Made with](https://img.shields.io/badge/made%20with-Supabase%20%7C%20Telegram-orange)

**Anonymous corruption-reporting platform for Bangladesh** — report bribery and corruption safely, in Bengali, with zero fear of exposure.

🔗 **Live demo:** https://imran-3478.github.io/Gush.khor/

---

## ✨ Features

- 🕵️ **Fully anonymous reporting** — every report gets a tracking code, no identity attached
- 📎 **Evidence upload** — attach images or PDFs to strengthen your report
- 🖥️ **Admin review dashboard** — moderators verify and act on reports
- 🔍 **Status tracking** — check your report's progress with your tracking code
- 🔔 **Telegram instant alerts** — admins get notified the second a report lands
- 🇧🇩 **Bengali-first UI** — built for the people who need it most

## 🔒 Privacy

- **No login required** to submit a report — ever
- Evidence is stored **privately** and served via expiring signed URLs
- Client-side protections against spam and metadata leaks

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, JavaScript |
| Database | Supabase Postgres (Row Level Security) |
| File storage | Supabase Storage (private bucket) |
| Serverless | Supabase Edge Functions |
| Alerts | Telegram Bot API |

## 📸 Screenshots

> Screenshots coming soon — try the [live demo](https://imran-3478.github.io/Gush.khor/).

## 🚀 Run Locally

Static site — no build step needed:

```bash
# Option 1: just open it
open index.html

# Option 2: serve it
npx serve .
