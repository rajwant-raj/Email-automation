##📧 Email Automation Agent using Google Gemini + Gradio

This project is an intelligent AI-powered email assistant that generates and sends professional emails based on user prompts using the free Google Gemini API. It includes a modern Gradio interface and works seamlessly on Google Colab.

🚀 Features
✅ Open-source and free (uses Gemini Pro from Google AI)

🧠 AI-generated professional email drafts

📤 Automatic email sending via Gmail SMTP

💻 Gradio-based web interface

📚 Colab-compatible (no setup required)

📁 Project Files

📦 EmailAutomationGemini
├── Email_Automation_Gemini_Gradio.ipynb   ← Main Colab notebook
├── README.md                              ← This file
🔧 Requirements
Python 3.7+

Google Colab (recommended)

Google Gemini API Key

Gmail account with App Password enabled

🔐 Setup Instructions
1. 🔑 Get Gemini API Key
Go to https://makersuite.google.com/app/apikey

Click "Create API Key"

Copy the key and paste it in the notebook under GEMINI_API_KEY

2. 📧 Set Gmail App Password
Visit: https://myaccount.google.com/apppasswords

Generate a new app password for "Mail" > "Windows Computer"

Copy and paste it in the notebook under SENDER_PASSWORD

⚠️ Do NOT use your regular Gmail password. App Password is mandatory.

▶️ How to Use
Open the notebook in Google Colab

Run all cells (top to bottom)

Fill out the Gradio form:

Email intent/prompt

Recipient email

Subject

Click Submit

The AI drafts and sends the email instantly!

🧪 Sample Prompt

Inform the team that the client meeting has been moved to Thursday at 2 PM due to scheduling conflicts.

💡 Example Use Cases

Leave applications

Meeting invites

Follow-up emails

Feedback requests

Polite reminders


→ AI-generated email appears
→ Status: ✅ Email sent successfully
📜 License
This project is licensed under the MIT License.
