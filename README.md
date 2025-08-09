# 📱 WhatsApp–Google Drive Assistant (n8n + Twilio)

Automate Google Drive actions directly from WhatsApp messages using **n8n** and **Twilio**.  
Send commands from WhatsApp, and the bot will process them and return results from Google Drive — all without writing a single line of backend code.

---

## 🚀 Features (Completed Till Now)
- ✅ Twilio WhatsApp Sandbox connected for incoming & outgoing messages.  
- ✅ Webhook in n8n to listen for WhatsApp messages.  
- ✅ Command Parser to split input into command and parameters.  
- ✅ Google Drive API integration for file/folder search.  
- ✅ Working workflow exported to JSON for version control.  

---

## 🛠 Tech Stack
- **n8n** – Workflow Automation Tool  
- **Twilio WhatsApp API** – For messaging integration  
- **Google Drive API** – File search & operations  
- **JavaScript** – For command parsing logic  

---

## 📂 Folder Structure
```
whatsapp-n8n-twilio/
│-- workflow.json # Exported n8n workflow
│-- README.md # Project documentation

```
---

## ⚙️ Setup Instructions

1. **Clone the Repository**

git clone https://github.com/Anupam11421/whatsapp-n8n-twilio.git
cd whatsapp-n8n-twilio

2.Import Workflow in n8n

Open n8n (local/cloud)

Go to Import from File

Select workflow.json

3.Configure Credentials

Twilio → Add Account SID & Auth Token from Twilio Console

Google Drive → Create OAuth credentials & connect account

4.Test the Workflow

Send message to your Twilio WhatsApp sandbox number

  LIST /ProjectX

Bot will search Google Drive and return matching files/folders.

📅 Roadmap (Next Steps)
Add support for UPLOAD & DELETE commands.

Multi-user authentication.

Deploy to cloud for 24/7 uptime.

## 👤 Developed By

**Anupam Tiwari**  
🔗 GitHub: [Anupam11421](https://github.com/Anupam11421)  
📧 Email: [tiwarianupam11421@gmail.com](mailto:tiwarianupam11421@gmail.com)
