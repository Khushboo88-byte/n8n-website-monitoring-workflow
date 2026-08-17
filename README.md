# n8n Website Monitoring & Gmail Automation

An automated website monitoring workflow built with n8n. It checks a website every minute, verifies its HTTP response status, detects whether the website is up or down, and creates a Gmail draft notification.

## 🚀 Features

- Automated website monitoring
- HTTP status checking
- Website up/down detection
- Conditional workflow logic
- Gmail notification automation
- Scheduled execution every minute

## 🔄 Workflow

Schedule Trigger → HTTP Request → Status Check → Website Up/Down → Gmail Draft

## 🛠️ Technologies Used

- n8n
- HTTP Request
- Gmail
- Workflow Automation

## 📌 How It Works

1. The Schedule Trigger runs the workflow every minute.
2. An HTTP Request checks the monitored website.
3. The workflow checks the HTTP response status.
4. If the status is `200`, the website is marked as **up**.
5. A Gmail draft is created with the website status update.

## 📂 Project File

`website-monitoring-workflow.json`

## 👩‍💻 Author

**Khushboo Raj Nagvanshi**

GitHub: https://github.com/Khushboo88-byte
