# 🌀 n8n Workflows Collection  
[![n8n](https://img.shields.io/badge/Automation-n8n-blue)](https://n8n.io/) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

## 📂 Repository Structure
n8n-workflows/
├── workflows/
│   ├── slack-automation/
│   │   ├── slack-reminder.json
│   │   └── README.md
│   ├── github-integration/
│   │   ├── auto-issues.json
│   │   └── README.md
└── docs/
    └── screenshots/

## 🚀 How to Use These Workflows
1. Clone or download this repository.  
2. Open your n8n instance (self-hosted or cloud).  
3. Go to **Workflows → Import from File**.  
4. Select the `.json` workflow file you want.  
5. Set up required credentials (Slack, GitHub, etc.).  
6. Activate the workflow!  

## 📋 Available Workflows
| Workflow | Description | Link |
|----------|-------------|------|
| Slack Daily Reminder | Sends automated reminders in Slack channels | [View](./workflows/slack-automation) |
| GitHub Auto-Issues | Creates GitHub issues from form submissions | [View](./workflows/github-integration) |
| Data Cleaning Pipeline | Cleans raw CSV data and stores in database | [View](./workflows/data-cleaning) |

## 🖼️ Screenshots
![Slack Reminder Workflow](./docs/screenshots/slack-reminder.png)

## 📜 License
Released under the [MIT License](LICENSE).  
Feel free to use and adapt these workflows for your own projects.  
