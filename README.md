## 🚀 IssueCoin AI — HR Automation System

AI-driven **HR & Payroll multi-agent automation** for **IssueCoin AI s.r.o.**, built on **Microsoft 365** and **Azure OpenAI**.
System automates **onboarding, attendance approvals, mandatory training** and internal email communication using enterprise workflow automation.

## 🤖 Multi-Agent Architecture

| Agent                          | Responsibility                                          | Technology                    |
| ------------------------------ | ------------------------------------------------------- | ----------------------------- |
| **IssueCoin AI (Chief Agent)** | Controls all HR sub-agents, communication & decisions   | Azure OpenAI                  |
| **IC-HR Agent**                | HR workflows orchestration, email actions               | Power Automate                |
| **Attendance Agent**           | Request approvals (holiday, sick day, home office…)     | Power Automate + SharePoint   |
| **On/Off-Boarding Agent**      | New hire announcements, reminders, pre-start checklists | SharePoint + Outlook          |
| **Training Agent**             | Compliance training (H&S, Fire Safety, GDPR)            | SharePoint + Email automation |


💼 All workflows work with **real company business identity**:
📧 denisa_pitnerova@IssueCoinAIsro.onmicrosoft.com

## 🔁 Automated Workflows
**✅ 1 — Attendance & Time Off Automation**
**Smart approval workflow**
**Status tracking in SharePoint (Pending → Approved/Rejected)**
**Automated personalized email to employee**
➡ “Your leave request has been approved.”
➡ “Your leave request has been rejected.”

**🧩 2 — Onboarding Automation**
**Welcome email with pre-start SharePoint checklist**
**Notification to HR & IT to prepare**:
User Access & Contract
Laptop & Workstation
H&S / GDPR / Fire Safety onboarding

**🎓 3 — Compliance Mandatory Training**
**Auto-assignment of 3 trainings**:
Health & Safety
Fire Protection
GDPR
**Tracking completion status in SharePoint**
**Auto-reminder after 7 days**

## 🛠️ Tech Stack

| Layer                | Service                                    |
| -------------------- | ------------------------------------------ |
| Workflow Engine      | **Microsoft Power Automate**               |
| Data Storage         | **SharePoint Online**                      |
| Identity & Email     | **Microsoft Entra ID (Azure AD)**, Outlook |
| AI Logic & Reasoning | **Azure OpenAI**                           |
| Deployment & Hosting | Microsoft 365 Business Basic               |

**🔐 Security** 

Entra ID secured access
No sensitive personal data exposed in GitHub
Minimal required privileges (least-privilege principle)

**📈 Future development** 

| Phase   | Upgrade                                           |
| ------- | ------------------------------------------------- |
| Phase 1 | Document signature automation + payroll summaries |
| Phase 2 | AI-driven decisions using company HR policies     |
| Phase 3 | Integration with n8n + RAG knowledge of labor law |
| Phase 4 | Self-service HR assistant chat for employees      |

**📎 Screenshots** 
👉 Will be added in next commit: onboarding emails, approval emails, SharePoint dashboards, workflow diagrams.

**👩‍💼 Author** 

Denisa Pitnerová
AI Automation & DevOps Engineer
IssueCoin AI s.r.o.

**⭐️ Support the project**

If you like this project, feel free to give it a ⭐ on GitHub — thank you!
