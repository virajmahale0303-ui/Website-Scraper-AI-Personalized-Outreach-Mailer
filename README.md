# Website-Scraper-AI-Personalized-Outreach-Mailer
This n8n workflow reads business names and website URLs from Google Sheets, scrapes website content, uses AI to generate personalized outreach emails, and automatically sends them via Gmail — enabling highly customized cold outreach at scale.

📘 README
🚀 Overview

This workflow automates personalized cold outreach by collecting website content from prospects and generating tailored emails using AI.
Instead of sending generic cold emails, this system analyzes each website to craft relevant and personalized messages — significantly improving reply rates.

⚙️ How It Works
1️⃣ Read Leads from Google Sheets
Retrieves:
Business Name
Website URL
Contact Email

2️⃣ Filter & Clean Data
Ensures valid websites and removes duplicates.

3️⃣ Fetch Website Content
Visits each website and extracts HTML content.

4️⃣ Extract & Convert Content
Parses page content.
Converts HTML → readable Markdown/text.

5️⃣ AI Page Summary
Summarizes the business website content.

6️⃣ Generate Personalized Email
AI crafts a customized outreach email based on:
Business niche
Website content
Value proposition

7️⃣ Send Email via Gmail
Sends personalized outreach email.

8️⃣ Append Results to Google Sheets
Logs outreach status and results.

📊 Input Data (Google Sheet)
Required columns:
Business Name
Website URL
Email Address

📤 Output
For each lead:
Website summary
Personalized email draft
Email sent status
Timestamp / tracking data

✉️ Example Personalization
Instead of:
“We help businesses grow online.”
The workflow generates:
“I came across your website and loved how you showcase your architectural projects. We help firms like yours attract premium clients through high-converting landing pages…”

🧰 Requirements
Accounts & Integrations
✅ Google Sheets
✅ Gmail account
✅ n8n (cloud or self-hosted)
✅ AI model access (OpenAI / Gemini / other LLM)

🔧 Setup Instructions
Import the workflow into n8n.
Connect:
Google Sheets credentials
Gmail account
AI model credentials
Ensure your sheet contains required columns.
Customize the email prompt to match your offer.
Execute the workflow.

🎯 Use Cases

✔ AI agencies & automation services
✔ B2B cold outreach
✔ Lead nurturing campaigns
✔ Freelancers & drop servicing
✔ SaaS customer acquisition

📈 Why This Workflow Works

✅ Hyper-personalized emails increase reply rates
✅ Eliminates manual research time
✅ Scales outreach efficiently
✅ Improves lead conversion quality

⚠️ Best Practices
Always verify email compliance laws (GDPR/CAN-SPAM).
Use sending limits to prevent Gmail restrictions.
Test email personalization before scaling.
Avoid sending bulk emails too quickly.

💰 Cost Considerations
AI usage cost per email generation
n8n hosting (if self-hosted)
Gmail sending limits

🔮 Future Improvements
LinkedIn personalization
Spam score optimization
Reply detection & follow-ups
CRM integration
Multi-step outreach sequences
