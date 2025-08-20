# ⏰ Daily Slack Reminder

This workflow sends a **daily standup reminder** message to a Slack channel at **9:00 AM (New York time)**.

---

## 📋 Workflow Details
- **Trigger**: Schedule (CRON `0 9 * * *`) → runs every day at 9:00 AM  
- **Action**: Post a message to a Slack channel  
- **Timezone**: America/New_York  
- **Message**:




---

## 🚀 How to Use
1. Import `daily-slack-reminder.json` into n8n:  
 - Open n8n → **Workflows → Import from File**.  
 - Select the JSON file.  

2. Open the **Post to Slack** node:  
 - Choose your Slack credentials.  
 - Replace the placeholder `channelId` with your real Slack channel ID.  

3. Save & **Activate** the workflow.  


---

## 🔒 Security Notes
- This workflow does **not** include credentials.  
- You must configure your own **Slack API credentials** in n8n.  
- Never commit credentials into JSON files.  

---

