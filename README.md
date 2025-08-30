# Generative AI Roadmap Scheduler

📅 A complete **learning roadmap + automation toolkit** for Generative AI.  
Built with **Google Sheets + Google Calendar + Apps Script**.

✅ Features:
- Learning roadmap (with curated YouTube videos, articles, tutorials)
- Sync tasks to Google Calendar (with reminders + phase colors)
- Auto-reschedule missed or completed sessions
- Daily + Weekly summary emails (with progress chart!)
- Visual Dashboard in Google Sheets

---

## 🚀 Getting Started

### 1. Import Roadmap
- Open [Google Sheets](https://sheets.google.com/)
- File → Import → Upload → use roadmap CSV file

### 2. Add Apps Script
- Extensions → Apps Script
- Copy-paste `apps-script/scheduler.gs`
- Save & authorize permissions

### 3. Sync Calendar
- Menu: **GenAI Scheduler → Sync All to Calendar**
- Events will appear in Google Calendar (color-coded by phase)

### 4. Track Progress
- Use Progress Tracking column (Not Started / In Progress / Completed)
- Completed sessions turn green in Calendar
- Dashboard auto-refreshes daily at 6 AM

### 5. Email Summaries
- Daily email (completed + rescheduled)
- Weekly email (with embedded progress chart + next week’s topics)

---

## 📊 Dashboard
- Dashboard tab shows progress breakdown, progress bar, upcoming sessions
- Auto-refresh daily at 6 AM

## 📧 Weekly Summary Email
- Sent every Saturday at 8 PM
- Includes chart + snapshot + upcoming week topics

---

## 📜 License
MIT License
