# N8n-Certificate-Eligibility-Generation

This project showcases an end-to-end automation workflow designed and implemented in n8n as part of a real-time project with Innomatics Research Labs. The system automates the evaluation of student performance and sends personalized certificate eligibility results — all without manual intervention.

**🎯 Objective**
To automatically evaluate student performance data and send personalized email notifications indicating their certificate eligibility category:
- 🥇 Gold
- 🥈 Silver
- 🥉 Bronze
- ❌ Not Eligible

**🔧 Project Workflow**
**📋 1. Data Collection**
- Student performance data captured through Google Forms
- Responses stored in Google Sheets

**⚙️ 2. Workflow Automation in n8n**
- The workflow uses the following n8n nodes:
-Google Sheet Node → Reads student data
- IF / Switch Node → Applies eligibility logic
- Email Node → Sends personalized certificate results
- Code Node (Optional) → Formats or preprocesses data

**🧮 3. Eligibility Logic**
**(Category	Criteria)**
- 🥇 Gold	Marks > 80, all tasks completed, quiz > 80, project presented
- 🥈 Silver	Marks 60–80, all tasks completed, quiz 60–80, project presented
- 🥉 Bronze	Marks 40–60, all tasks completed, quiz 40–60, project presented
- ❌ Not Eligible	Does not meet the above criteria

**📧 Outcome**
- Each student receives a personalized email with:
- Their certificate category
- A performance message
- Encouragement or next steps if not eligible

**This automation makes the process:**
✔️ Hands-free
✔️ Accurate
✔️ Scalable
✔️ Time-efficient

**💡 Key Learnings**
- Through this real-time project, I gained hands-on experience in:
- Workflow automation with n8n
- Conditional branching & logic building
- Google Workspace integration (Forms + Sheets)
- Email automation for real-world academic workflows
- Error handling and clean workflow structuring

**📸 Screenshots**
<img width="1919" height="1068" alt="Certification Eligibilty Screenshot" src="https://github.com/user-attachments/assets/177393ff-599f-4549-88d3-c03209f8e546" />
