# n8n-sme-sentiment-ai
# 🚀 Automated SME Customer Sentiment Analysis

## 📌 Project Overview
An end-to-end automated workflow designed to help SMEs analyze customer feedback in real-time. This project leverages **n8n** to connect LINE Official Account messages with GenAI (LLMs) to automatically classify customer sentiments and extract key insights without manual data entry.
![Uploading Image_25690709_190616_393.webp…]()


## 🛠️ Tech Stack & Tools
* **Workflow Automation:** n8n (Node-based automation)
* **AI & NLP:** GenAI / LLM APIs (for sentiment classification)
* **Data Sources/Integrations:** LINE OA API, Webhooks
* **Storage/Dashboarding:** Google Sheets / BI Tools

## 💡 Key Highlights & Business Impact
* **100% Automated Pipeline:** Eliminated manual data extraction and tagging.
* **Real-World Deployment:** Successfully deployed and tested by **6 active SME test users**.
* **Actionable Insights:** Enabled business owners to immediately identify negative feedback and respond faster.

## 📂 Repository Contents
* `workflow_export.json`: The raw n8n workflow file. (You can easily import this into your local n8n instance to see the pipeline structure).
* *(Note: API keys and sensitive credentials have been removed for security purposes).*

## ⚙️ How to Use
1. Install [n8n](https://n8n.io/).
2. Go to the workflows tab and click **Import from File**.
3. Select the `.json` file from this repository.
4. Re-configure the credentials (LINE API, LLM API) to test the workflow.
