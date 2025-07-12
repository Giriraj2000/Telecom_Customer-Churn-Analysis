
# Introduction to Churn Analysis:
In today’s competitive business environment, retaining customers is crucial for long-term success. Churn analysis is a key technique used to understand and reduce this customer attrition. It involves examining customer data to identify patterns and reasons behind customer departures. By using advanced data analytics and machine learning, businesses can predict which customers are at risk of leaving and understand the factors driving their decisions. This knowledge allows companies to take proactive steps to improve customer satisfaction and loyalty.

# Target Audience:

Although this project focuses on churn analysis for a telecom firm, the techniques and insights are applicable across various industries. From retail and finance to healthcare and beyond, any business that values customer retention can benefit from churn analysis. We will explore the methods, tools, and best practices for reducing churn and improving customer loyalty, transforming data into actionable insights for sustained success.
___________________________________________________________________________________________________________________________________________________________________________________________

# Telecom-Customer-Churn-Analysis

# 📌 Problem Statement: Telecom Customer Churn Prediction
In the highly competitive telecom industry, retaining existing customers is more cost-effective than acquiring new ones. However, telecom companies face significant challenges in identifying customers who are likely to discontinue their services (churn). A high churn rate directly impacts revenue, customer acquisition costs, and brand loyalty.

The goal of this project is to analyze historical customer data and develop a predictive model that can accurately identify customers who are at high risk of churning. This will help the company implement targeted retention strategies to reduce churn and improve customer satisfaction.

# ✅ Objectives:
Understand the key factors that contribute to customer churn.

Perform exploratory data analysis (EDA) on customer demographics, service usage, and account details.

Perform data cleaning, transformation, and feature engineering.

Engineer relevant features to improve model performance.

Build and evaluate machine learning models to predict churn likelihood.

Develop an interactive Power BI dashboard to visualize churn insights and support business decisions.

# 📦 Dataset
The dataset contains customer-level information including:

Demographics: Gender, senior citizen status, partner/dependents

Account Information: Tenure, contract type, payment method, monthly and total charges

Services: Phone, internet, streaming, online security, tech support

Target Variable: Churn (Yes/No)

# 🛠️ Requirements
Tools & Technologies:
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Power BI (for visualization)

Jupyter Notebook

Microsoft SQL Server (for ETL) 

# 🔄 Project Workflow
1. 📥 Data Collection
Loaded telecom churn data from CSV file and Microsoft SQL Server.

2. 🧹 Data Cleaning
Removed duplicates and Handled null values.

Converted data types (e.g., TotalCharges to float).

Handled categorical values.

3. 🧠 Feature Engineering
Created new features like tenure_bin.

One-hot encoded categorical variables.

4. 📊 Exploratory Data Analysis (EDA)
Analyzed churn distribution.

Perform Univariate, Bivariate and Multivariate Analysis.

Visualized churn by contract type, services used, payment method, etc.

5. 🤖 Model Building
Split data into training and test sets.

Tried multiple classification algorithms: Decision Tree & Random Forest.

Evaluated using accuracy, precision, recall, and F1 score.

6. 📈 Model Evaluation
Compared model performance using classification report and confusion matrix.

Selected the best-performing model based on business priorities (e.g., minimizing false negatives).

7. 📉 Power BI Dashboard
Imported cleaned data into Power BI.

Transformed the data in the Power Query.

Built visuals for:

Churn by demographics: Gender, Senior Citizen, Dependent, Partners

Churn by Account Information: Tenure, Contract, Payment Method, Billing Type.

Churners & Non-Churner Behaviour based on Monthly Charges and Total Charges.

Churn by services subscribed.



KPIs: Total Customers, Churn Rate, Retention Rate






__________________________________________________________________________________________________________________________________________________________________________________________

# Key Insights:

Senior citizens churn more.

Customers without dependents have a higher churn rate.

No significant churn difference between male and female customers.

Customers without partners are slightly more likely to churn.

Newer customers churning more.

Churn reduce with long-term contracts.

Electronic check users more likely to churn.

Customers without tech support are most likely to churn.

Churn paying high Monthly Charges are more likely to churn.

Customers having less monthly charges and less total charges are less likely to churn.

Around 47% customers got churned having tenure less than 1 Year. Churn rate decreases as Tenure Increases.

41.89% Customers got churned using the fibre optic services. 

Customers opted for paperless billing are more likely to churn.
__________________________________________________________________________________________________________________________________________________________________________________________

# 📌 Churn Reduction Strategy: Data-Driven Recommendations
🔍 Insight-Based Solutions:
🧓 1. Senior Citizens Churn More
Solution:

Launch a Senior Care Plan with:

Simplified plans

Dedicated customer care lines

Personalized onboarding and technical assistance

Provide discounts or loyalty points for senior citizens with tenure > 1 year.

👨‍👧 2. Customers Without Dependents & Without Partners Churn More
Solution:

These customers may feel less committed or receive fewer benefits from bundled services.

Offer solo plans with high value for single users:

Add-on streaming or cloud services

“Customize your pack” flexibility

Use engagement emails or app messages with tailored offers.

🧑‍🤝‍🧑 3. No Significant Churn Difference by Gender
Solution:

No specific gender-targeted strategy needed.

Continue focusing on usage-based and tenure-based segments.

🧾 4. Electronic Check Users Churn More
Solution:

Educate users on secure and easier payment methods (autopay, credit card).

Incentivize switching with:

₹50–₹100 bill credits

One-month free add-on for switching to autopay

Flag electronic check users for proactive retention messaging.

🧑‍💻 5. New Customers & Low Tenure (≤1 year) Have High Churn (47%)
Solution:

Strengthen onboarding experience:

Welcome call, email guides, setup support

Create a "First-Year Loyalty Program" with benefits for staying 3, 6, and 12 months.

Monitor satisfaction of customers in their first 90 days using surveys or usage alerts.

📄 6. Churn Reduces with Long-Term Contracts
Solution:

Promote 12- and 24-month plans with:

Lower monthly pricing

Free service months or upgrade options

Offer exit penalties with a grace clause to reduce early drop-offs.

🔧 7. Customers Without Tech Support Churn More
Solution:

Bundle basic tech support into all plans or promote it at a discount.

Provide 1-month free trial of tech support for at-risk customers.

💸 8. High Monthly Charges → High Churn
Solution:

Introduce value packs for high spenders:

Premium services + loyalty discounts

Conduct a usage vs. cost analysis to suggest better-suited plans

Offer custom retention plans during offboarding calls or on My Account portal.

📉 9. Low Charges → Low Churn
Solution:

These users are stable but may churn if costs increase suddenly.

Ensure price transparency and notify about upcoming hikes.

Consider gradual pricing increases for long-tenure users to avoid dissatisfaction.

🌐 10. 41.89% Churn Among Fiber Optic Users
Solution:

Audit Fiber Optic service quality across locations.

Collect and resolve complaints faster with a Fiber First Response Team.

Offer free upgrades, reduced prices, or bundles for fiber users at risk.

🧾 11. Paperless Billing Customers More Likely to Churn
Solution:

Add value to paperless billing (e.g., e-bill cashback, digital-only discounts).

Ensure that e-bills are easy to understand and sent with reminders.





