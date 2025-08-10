# WhatsApp-Driven Google Drive Assistant (n8n Workflow)

This project is an **n8n workflow** that integrates **Twilio WhatsApp**, **Google Drive**, and automation logic to perform actions such as:
- Listing files
- Deleting files
- Moving files between folders

The workflow is designed to run locally with **n8n** and uses **ngrok** for public URL forwarding.

---

## 🚀 Features
- **WhatsApp Command Interface** — Send commands via WhatsApp to interact with Google Drive.
- **Google Drive File Operations** — List, delete, and move files.
- **Webhook Integration** — Uses Twilio's WhatsApp webhook to trigger the workflow.

---

## 📦 Requirements
Before running, install:
- [Node.js](https://nodejs.org/)
- [n8n](https://n8n.io/)
- [Docker](https://www.docker.com/) (optional, for containerized execution)
- [ngrok](https://ngrok.com/)
- Twilio account (for WhatsApp API)
- Google Cloud project with Drive API enabled

---

## ⚙️ Setup Instructions
1. Install & Run n8n with Docker.
2. Set up ngrok.
3. Import Workflow.
4. Configure Environment Variables.
   - TWILIO_ACCOUNT_SID=your_sid
   - TWILIO_AUTH_TOKEN=your_token
   - GOOGLE_CLIENT_ID=your_id
   - GOOGLE_CLIENT_SECRET=your_secret
5. Usage
   - list
   - delete <file_id>
   - move <file_id> <folder_id>

