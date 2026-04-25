# 🔥 AI-Powered Steel Plant Energy Analytics & Slack Automation

## 📌 Project Overview
This project is an end-to-end **AI-powered data analytics pipeline** built for analyzing industrial energy consumption in a steel manufacturing environment.
It combines **data analysis, visualization, and AI-generated insights** with **automated Slack reporting**, simulating a real-world business analytics workflow used in modern industries.

## 🎯 Objectives
- Analyze industrial energy consumption data  
- Identify patterns, inefficiencies, and anomalies  
- Generate actionable business insights using AI  
- Visualize data through professional charts  
- Automate reporting and deliver results to Slack  

## 🧠 Key Features
- 📊 Exploratory Data Analysis (EDA)  
- 📈 Multiple professional visualizations:
  - Energy consumption trend  
  - Load type distribution  
  - Correlation heatmap  
  - Peak usage analysis  
  - Data distribution  
- 🤖 AI-powered insights using LangChain + OpenAI  
- ⚠️ Anomaly detection (top energy spikes)  
- 📩 Automated Slack reporting with charts  

## 🧰 Tech Stack
- **Python**
- **Pandas** – Data analysis  
- **Matplotlib & Seaborn** – Visualization  
- **LangChain + OpenAI** – AI insights generation  
- **KaggleHub** – Dataset integration  
- **Slack SDK** – Automation & reporting  
- **Google Colab** – Development environment  

## 📂 Dataset
- **Source:** Kaggle  
- **Dataset:** Steel Industry Energy Consumption 

### Includes:
- Energy Usage (kWh)  
- Reactive Power  
- Power Factor  
- CO₂ Emissions  
- Load Type  
- Time-based industrial data  

## ⚙️ Workflow
### Step-by-Step:
1. Load dataset using KaggleHub  
2. Perform exploratory data analysis  
3. Generate multiple visualizations  
4. Detect peak usage and anomalies  
5. Use LangChain to generate business insights  
6. Send insights + charts automatically to Slack 

## 📊 Visualizations
The project generates:

![Load Type Distribution](https://raw.githubusercontent.com/chandannath500/Langchain_Steel_Industry_Energy_Consumption/main/images/load_type.png)

![Correlation Heatmap](https://raw.githubusercontent.com/chandannath500/Langchain_Steel_Industry_Energy_Consumption/main/images/correlation.png)

![Top Energy Usage](https://raw.githubusercontent.com/chandannath500/Langchain_Steel_Industry_Energy_Consumption/main/images/top_usage.png)

![Energy Usage Distribution](https://raw.githubusercontent.com/chandannath500/Langchain_Steel_Industry_Energy_Consumption/main/images/distribution.png)

## 🤖 AI Insights (LangChain)
The system uses **LangChain + OpenAI** to:
- Interpret dataset statistics  
- Identify patterns and inefficiencies  
- Highlight anomalies  
- Generate business-focused recommendations  

## 📩 Slack Automation
- Sends structured AI insights  
- Uploads all charts automatically  
- Delivers a complete report in real-time

## 🚀 How to Run
### 1. Install Dependencies
```bash
pip install pandas matplotlib seaborn slack-sdk kagglehub langchain-openai
```

### 2. Set Environment Variables
```python
import os
os.environ["OPENAI_API_KEY"] = "your_openai_key"
os.environ["SLACK_USER_TOKEN"] = "your_slack_token"
```

### 3. Run Notebook
Execute all cells to:
- Load data
- Analyze dataset
- Generate charts
- Create AI insights
- Send report to Slack

## 💼 Business Impact
- Identifies energy inefficiencies
- Detects abnormal consumption patterns
- Supports cost optimization decisions
- Enables real-time monitoring via Slack

## 💼 Real-World Use Cases
- Manufacturing energy monitoring
- Smart factory analytics
- Industrial IoT systems
- Cost optimization dashboards

## 🔮 Future Enhancements
- 📊 Power BI / Tableau dashboard integration
- 🤖 Predictive analytics (forecasting energy usage)
- ⏱ Real-time streaming data pipeline
- ☁️ Cloud deployment (AWS/GCP)
- 📉 Automated cost-saving recommendations

## 👨‍💻 Author
**Chandan Nath**  
IT Project Manager | Data Analyst

## ⭐ Project Highlights
- ✔ AI + Data Analytics Integration
- ✔ Real-world industrial dataset
- ✔ Automated reporting system
- ✔ Business-focused insights
- ✔ End-to-end pipeline