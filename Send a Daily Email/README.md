# 📩 Daily Email Digest

This workflow sends a **daily email** at **8:00 AM (New York time)**.

---

## 📋 Workflow Details
- **Trigger**: Schedule (CRON `0 8 * * *`) → runs every day at 8:00 AM  
- **Action**: Send an email via SMTP  
- **Timezone**: America/New_York  
- **Message**:


---

## 🚀 How to Use
1. Import `daily-email-digest.json` into n8n.  
2. Open the **Send Email** node:  
 - Add your SMTP credentials (Gmail, Outlook, etc.).  
 - Replace `you@example.com` and `recipient@example.com`.  
3. Save & **Activate** the workflow.  

---

## 🔒 Security Notes
- Credentials are not included — you must configure SMTP in n8n.  
- Do not commit API keys or secrets into JSON.  

---

