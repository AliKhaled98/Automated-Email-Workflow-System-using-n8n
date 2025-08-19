
# Automated Email Workflow System (n8n)

## 📌 Overview
This project automates form response collection and personalized email replies using **n8n**.  
It connects Google Forms → Google Sheets → Gmail with conditional branching to handle responses intelligently.

## 🔄 Workflow
- **Step 1**: User submits a Google Form  
- **Step 2**: Data is stored in Google Sheets  
- **Step 3**: n8n workflow applies conditions & branching  
- **Step 4**: Personalized Gmail responses are sent  

## 🛠️ Tools & Technologies
- [n8n](https://n8n.io/) – No-code workflow automation  
- Google Forms & Sheets – Data collection and storage  
- Gmail API – Automated personalized responses  

## 📷 Workflow Diagram
![Workflow Screenshot](assets/workflow_screenshot.png)

## 🚀 Setup
1. Import the JSON file in `workflow/automated_email_system.json` into your n8n instance.  
2. Configure Google credentials for Sheets + Gmail.  
3. Test with sample form submissions.  

## 🎯 Learning Outcomes
- Hands-on with **no-code automation** using n8n  
- Integration of Google APIs with workflow automation  
- Building scalable solutions for real-world productivity challenges  
