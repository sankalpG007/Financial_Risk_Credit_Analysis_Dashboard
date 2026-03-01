💳 Financial Risk & Customer Credit Analysis Dashboard
📌 Project Overview

This project is an end-to-end Financial Risk Analytics solution built using Python, SQL, and Power BI. The objective was to analyze real-world Lending Club loan data (164K+ records) to evaluate credit risk, identify high-risk borrower segments, and quantify portfolio exposure and monetary loss.

The dashboard simulates a real banking risk analytics workflow, focusing on exposure analysis, default rate monitoring, and business-driven segmentation.

🎯 Business Objective

Financial institutions must balance loan growth with risk control. This project answers key risk questions:

What is the overall portfolio default rate?

Which credit grades contribute the highest monetary loss?

How does Debt-to-Income (DTI) impact default probability?

Which borrower segments should be flagged for risk?

🛠 Tools & Technologies Used

Python (Pandas, NumPy) – Data cleaning & feature engineering

PostgreSQL – Risk segmentation & exposure analysis

Power BI – Interactive executive dashboard

GitHub – Version control & project documentation

📊 Dataset

Lending Club Accepted Loans (2007–2018)

164,909 cleaned loan records used for analysis

Key variables:

Loan Amount

Interest Rate

Credit Grade

Income Segment

DTI Category

Loan Status

🔍 Key Analysis Performed
1️⃣ Portfolio Risk Analysis

Calculated overall Default Rate (~19.6%)

Computed Portfolio Exposure (~₹2.45B)

Estimated Portfolio Loss Rate

2️⃣ Exposure-Based Risk Assessment

Identified that Grade C contributed highest monetary loss due to large exposure volume

Demonstrated that high default percentage does not always mean highest financial loss

3️⃣ Risk Driver Identification

Verified that Very High DTI borrowers have significantly higher default probability

Observed inverse relationship between income level and default rate

Analyzed default variation across home ownership categories

4️⃣ Interactive Executive Dashboard

Built dynamic filters for grade, income segment, DTI category, purpose, and term

Enabled real-time segmentation analysis for risk decision-making

📈 Key Insights

Default rate increases progressively from Grade A to Grade G

Grade C contributes highest monetary exposure loss

Very High DTI borrowers show significantly elevated risk

Lower-income segments exhibit higher probability of default

🧠 What I Learned

How to design analytics with business impact, not just visuals

How to move from raw data → SQL modeling → executive BI storytelling

How exposure analysis differs from percentage-based risk evaluation

How to build a professional-grade dashboard aligned with stakeholder needs

🚀 Future Improvements

Implement predictive credit risk model (Logistic Regression)

Add probability of default scoring

Deploy dashboard via Streamlit for public access

Integrate automated data refresh pipeline
