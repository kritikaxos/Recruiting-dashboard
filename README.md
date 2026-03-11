# sample-recruiting-dashboard
# 📊 NovaMind AI — Recruiting Operations Dashboard
A live talent ops dashboard that reads directly from Google Sheets to give recruiting leads and Chiefs of Staff real-time visibility into their hiring pipeline — no ATS required.

🎥 **Demo Video:** [Watch the demo](https://drive.google.com/file/d/1U88H6VUFOTrINLL1duxzlk8aNIyPErVS/view?usp=drive_link)
🔗 **Live Dashboard:** [View live](https://haeshadae.github.io/sample-recruiting-dashboard/)
🗂 **Sample Data:** [View Google Sheet](https://docs.google.com/spreadsheets/d/1PXP8-SZ07zLTGen53n8fXxz6gbD0GVY6abkRkDWKMM0/edit?gid=987125841#gid=987125841)

---
## ✨ What It Does
1. **Pipeline Funnel** — tracks candidates across Applied → Recruiter Screen → HM Screen → Final Round → Offer Extended → Hired
2. **Time to Hire by Role** — color-coded bar chart showing which roles are slow (red), moderate (yellow), or fast (green)
3. **Candidate Source Mix** — donut chart showing where candidates are coming from (LinkedIn, Referral, Inbound, etc.)
4. **Open Requisitions** — grouped by role with days open and urgency status (On Track / Slow / Urgent)
5. **Live KPIs** — avg time to hire, open reqs, active candidates, offer accept rate, pipeline conversion

---
## 🧠 Why I Built This
Some early-stage teams track recruiting in spreadsheets but have no visibility into pipeline health. I wanted to show how a lightweight ops dashboard could sit on top of a tool they already use — no new software, no migration, no $30K ATS.

---
## ⚙️ Architecture
Google Sheets → Sheets API → Vanilla JS Dashboard → GitHub Pages

---
## 🔒 Security
API key is restricted to the Google Sheets API only and locked to the deployed domain. No keys are stored in this repository.

---
Built with vanilla JS, Chart.js, and the Google Sheets API.
---
