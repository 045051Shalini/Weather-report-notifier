# Weather-report-notifier
# 🌦️ Weather Report Notifier using n8n

An automated **Weather Report Notification System** built using **n8n**. The workflow monitors a weather report document stored in Google Drive, extracts its content, summarizes it using an AI model, and sends the summarized report as an SMS using Twilio.

---

## 🚀 Features

- 📂 Automatically detects weather report files from Google Drive.
- 📄 Extracts text from uploaded DOCX files.
- 🤖 Generates a concise weather summary using AI.
- 📱 Sends the summarized report as an SMS through Twilio.
- ⚡ Fully automated workflow built with n8n.

---

## 🛠️ Technologies Used

- n8n
- Google Drive
- AI Text Summarization
- Twilio SMS API

---

## 📌 Workflow

The complete automation workflow is shown below.
<img width="714" height="373" alt="image" src="https://github.com/user-attachments/assets/5bf9b404-dc86-4daa-be04-dd63d6067e50" />


---

## ▶️ Workflow Execution

The following video demonstrates the successful execution of the workflow.

https://github.com/user-attachments/assets/0bbf603a-733c-429b-850d-7d232c614062

---

## 📱 SMS Output

The AI-generated weather summary is successfully delivered via SMS.

| SMS Screenshot 1 | SMS Screenshot 2 |
|------------------|------------------|
| <img src="https://github.com/user-attachments/assets/4c8c2ad4-5a30-4ab8-b65d-69811882d3fb" width="300"> | <img src="https://github.com/user-attachments/assets/e89c0360-eff3-4e90-a81e-11c91091e609" width="300"> |

---

## 📄 Sample Weather Report

The weather report used to test this workflow can be found here:

**15 June Mumbai Weather Report**

https://github.com/045051Shalini/Weather-report-notifier/blob/main/15%20June%20Mumbai%20.docx

---

## 📂 Workflow Steps

1. Detect a new weather report in Google Drive.
2. Download the report document.
3. Extract text from the document.
4. Summarize the report using AI.
5. Send the summarized report as an SMS via Twilio.

---
## 📥 Import Workflow

The complete n8n workflow is available in this repository.

**Workflow JSON**

https://github.com/045051Shalini/Weather-report-notifier/blob/3c48565544c813bfe44549ef8f714e3291106da9/RAG%20Weather%20Report%20Notifier%20(Drive%20%E2%86%92%20Vector%20DB%20%E2%86%92%20SMS).json

To import the workflow:

1. Open n8n.
2. Click **Import from File**.
3. Select the downloaded JSON workflow.
4. Configure your credentials:
   - Google Drive
   - OpenAI
   - Twilio
5. Execute the workflow.
---
## 📈 Future Enhancements

- WhatsApp Notifications
- Email Notifications
- Multi-city Weather Reports
- Daily Scheduled Automation
- PDF Report Support
- Weather Dashboard Integration

---
