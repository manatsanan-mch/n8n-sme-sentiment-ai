# 🚀 Automated SME Customer Sentiment Analysis

## 📌 Project Overview
An end-to-end automated workflow designed to help SMEs analyze customer feedback in real-time. This project leverages **n8n** to connect LINE Official Account messages with GenAI (LLMs) to automatically classify customer sentiments and extract key insights without manual data entry.
<img width="1253" height="623" alt="<img width="1600" height="522" alt="1000065172" src="https://github.com/user-attachments/assets/addb4df4-9232-4a2e-bf9f-1e290a7f7703" />
"

## 🛠️ Tech Stack & Tools
* **Workflow Automation:** n8n (Node-based automation)
* **AI & NLP:** GenAI / LLM APIs (for sentiment classification)
* **Data Sources/Integrations:** LINE OA API, Webhooks
* **Storage/Dashboarding:** Google Sheets / BI Tools

## 💡 Key Highlights & Business Impact
* **Zero Manual Intervention:** Fully automated end-to-end pipeline that eliminates manual data extraction, tagging, and logging.
* **Real-World Deployment:** Successfully deployed and tested with **6 active SME test users**.
* **Actionable Insights:** Enables business owners to immediately identify negative feedback and respond in real-time.

## 📂 Repository Contents
* `workflow_export.json`: The raw n8n workflow file. (You can easily import this into your local n8n instance to see the pipeline structure).
* *(Note: All API keys and sensitive credentials have been replaced with placeholders e.g., `YOUR_LINE_CHANNEL_ACCESS_TOKEN` for security purposes).*

## ⚙️ How to Use
1. Install [n8n](https://n8n.io/).
2. Go to the workflows tab and click **Import from File**.
3. Select the `.json` file from this repository.
4. Re-configure the credentials (LINE API, LLM API) to test the workflow.

## 📊 Live Dashboards & Previews
## 🔗 Direct Project Links
Click the badges below to directly view the live data outputs:

[![Looker Studio](https://img.shields.io/badge/Looker_Studio-Live_Dashboard-blue?style=for-the-badge&logo=googlecloud&logoColor=white)](https://datastudio.google.com/s/lmC0nS_JDuM)

[![Google Sheets](https://img.shields.io/badge/Google_Sheets-Database_View-green?style=for-the-badge&logo=googlesheets&logoColor=white)](https://docs.google.com/spreadsheets/d/1XqixdYgmsd9SPp59CxfjZl82ogS9keV7bbKVPh8ZVj8/edit?usp=sharing)
