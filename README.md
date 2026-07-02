✈️ Unlocking Behavioral Intelligence in Airline Loyalty Programs
An end-to-end data analytics and predictive modeling project designed to move beyond traditional points-based metrics. This project identifies behavioral disengagement, discovers genuinely valuable customer clusters, and delivers actionable retention blueprints—culminating in a dynamic, stakeholder-ready Excel dashboard.

📖 Project Overview
Traditional loyalty metrics often fail to capture true customer engagement, relying too heavily on standard Customer Lifetime Value (CLV) and point balances. This project analyzes historical flight and loyalty data to predict churn based on behavioral disengagement before it happens, segment customers into actionable groups, and deploy targeted retention strategies via an accessible, interactive Excel dashboard.

🎯 Business Objectives
This repository addresses three core business challenges:
Early Churn Prediction: Identifying behavioral disengagement markers without relying on future data or explicit cancellation events.
Advanced Customer Segmentation: Moving beyond standard RFM (Recency, Frequency, Monetary) to uncover genuinely valuable clusters based on booking behaviors, redemption patterns, and engagement trends.
Smart Retention Blueprints: Creating scalable, step-by-step intervention strategies tailored to specific at-risk segments to maximize ROI on marketing spend.

📊 Data Overview
Scope: 16,700 Canadian airline loyalty members.
Timeframe: 2012 – 2018.
Features: The dataset includes enrollment details, point accumulation/redemption histories, flight frequencies, demographic data, and seasonal engagement metrics.

🚀 Key Deliverables
1. Predictive Churn Modeling
Built and evaluated classification models using Python to predict the probability of a user fading from the program.

Focus: High recall for early detection.

Evaluation: Precision-Recall curves, AUC-ROC, and feature importance analysis highlighting the most critical behavioral triggers.

2. Behavioral Segmentation
Identified highly distinct customer profiles, including:

Fading Gold: Historically high-value members showing sudden drops in flight frequency or engagement.

Points Hoarders: Members accumulating vast sums of points without redeeming, signaling a lack of perceived program utility.

Rising Stars: Newer or previously low-tier members exhibiting rapid growth in organic point accumulation.

3. Interactive Excel Dashboard
Translated complex machine learning outputs into a dynamic Excel dashboard designed for non-technical stakeholders (CMOs, CFOs). Features include real-time segment filtering via slicers, KPI tracking, and automated retention blueprint logic.

📂 Repository Structure
Plaintext
├── data/                   # Raw and processed datasets (Ignored in .gitignore)
├── notebooks/              # Jupyter notebooks for EDA, modeling, and segmentation
│   ├── 01_data_cleaning.ipynb
│   ├── 02_churn_prediction.ipynb
│   └── 03_customer_segmentation.ipynb
├── dashboard/              # Contains the interactive Excel dashboard
│   └── Airline_Loyalty_Dashboard.xlsx
├── reports/                # Final written reports and presentation materials
│   └── final_technical_report.pdf
├── requirements.txt        # Python package dependencies
└── README.md               # Project documentation
💻 Getting Started
Prerequisites
Python 3.8+ for running the data processing and modeling scripts.
Microsoft Excel (2016 or newer / Office 365) to view and interact with the dashboard.

Installation
Clone the repository:

Bash
git clone https://github.com/yourusername/airline-loyalty-analytics.git
Navigate to the project directory:

Bash
cd airline-loyalty-analytics
Install the required Python dependencies:

Bash
pip install -r requirements.txt
📈 Interactive Excel Dashboard
The crown jewel of this project's presentation is the Airline_Loyalty_Dashboard.xlsx file located in the /dashboard folder.

Dashboard Features:
Dynamic Slicers: Filter the data by customer segment, year, and loyalty tier to instantly update KPIs.
Risk Scoring Visuals: Pivot charts tracking the distribution of churn-risk across different customer demographics.
Blueprint Triggers: A dedicated view mapping out the exact behavioral thresholds and recommended marketing interventions (e.g., status accelerators, partner offers) for at-risk users.
To view the dashboard, simply download the .xlsx file and open it locally in Microsoft Excel. Ensure macros/content are enabled if prompted to allow pivot tables to refresh.
