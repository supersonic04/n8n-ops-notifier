# ⚙️ n8n Ops Notifier

A simple but flexible n8n workflow to automate operational alerts using data from APIs, SQL queries, or spreadsheets.

Designed for use in operations-heavy sectors like emergency services, logistics, utilities, and manufacturing — where **speed and clarity of alerts can reduce downtime and risk**.

---

## 🔄 What It Does

- Queries a source every 1–5 minutes (API, SQL, or Google Sheets)
- Filters results based on status, severity, or timestamp
- Sends formatted alert messages to:
  - ✅ Microsoft Teams
  - ✅ Slack
  - ✅ Email
  - ✅ SMS (Twilio or others)

---

## 🧠 Example Use Cases

| Sector              | Example Alert                                                       |
|---------------------|----------------------------------------------------------------------|
| Emergency Services  | “Unit 142 is now out of service – backup unit required”               |
| Logistics           | “Delivery route 6 is delayed – ETA updated to 3:45pm”              |
| Manufacturing       | “Line 4 temperature exceeded 80°C – check cooling system”          |
| Utilities           | “Substation fault detected at 16:02 – crew dispatched”             |
| Tech Ops            | “Service ‘API-A’ returned 5xx error >10 times in 5 mins”           |

---

## 🛠️ Tools & Tech

- [n8n](https://n8n.io) – low-code automation platform
- Any SQL DB (PostgreSQL, MySQL, etc.)
- Optional: REST APIs, Google Sheets, Twilio
- Messaging integrations: Microsoft Teams, Slack, Email

---

## 🚀 Quick Start

1. Import the `.json` file into your n8n instance
2. Set up your credentials for API, DB, or Sheets
3. Customize alert message and recipients
4. Test, deploy, and monitor

---

## 📸 Screenshots

![Workflow Overview](./screenshots/flow-overview.png)
![Sample Output](./screenshots/sample-output.png)

---

## 📫 Feedback & Contributions

Ideas or improvements? Open an issue or fork this repo.  
Built and maintained by [@supersonic04](https://github.com/supersonic04) as part of [Emberlytic](https://emberlytic.com)

---

## 🔐 License

MIT — fork it, adapt it, ship it.
