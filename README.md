# Customer-churn-data-analysis ![tableau_label](images/tableau_label.png)
Tableau visualisation of customer segmentation and behavioural patterns for exploratory data analysis (EDA) and churn modelling
## Interactive Dashboard
View the interactive Tableau dashboard here:  
https://public.tableau.com/views/YourProjectName/Dashboard1


customer-service-churn-analysis-tableau/
│
├── README.md
├── data/
│   └── Customer_Churn_Data_Cleaned.xlsx
│
├── tableau/
│   └── Customer_Service_Churn.twbx   (optional)
│
└── reports/
    └── Churn_Analysis_Report.pdf
Mention Tableau version used
    If the dataset is from Forage / Lloyds:
You may replace the Excel file with a dataset description instead.
Customer Service Interaction Analysis and Churn Risk Assessment
This project analyses customer churn behaviour using customer service interaction data. The objective is to identify early churn signals by examining interaction frequency, interaction type, resolution outcomes, and recency of the last interaction.

Tools and Technologies
Tableau Public
Microsoft Excel
GitHub

Dataset Description
The dataset is sourced from the Lloyds Bank Virtual Experience programme on Forage. It contains anonymised customer service interaction records, including interaction type, resolution status, interaction dates, and churn indicators.

Data Preparation
Data cleaning and preparation were performed in Excel and Tableau. This included validation of categorical fields, detection of outliers in numerical variables such as age and interaction counts, handling of missing values, and creation of derived features such as interaction frequency per customer and recency of last interaction.

Analysis Overview
The analysis focuses on:
• Churn rate by interaction type
• Complaint frequency and resolution outcomes
• Repeated interactions and service fatigue
• Recency of last interaction as an early churn signal

Customer-level metrics were created using Tableau LOD calculations to ensure accurate aggregation.

Key Insights
Customers with repeated service interactions show higher churn risk, particularly when issues remain unresolved. Complaint-related interactions are disproportionately represented among churned customers, while prolonged inactivity following an unresolved final interaction strongly indicates disengagement.

Tableau Dashboard
View the interactive dashboard here:
[Paste Tableau Public link]

Future Work
This dataset could be extended into predictive modelling by encoding categorical variables and scaling numerical features for machine-learning algorithms.

Step 5: Add screenshots (optional but powerful)
Take 1–2 clean screenshots of:
• the full dashboard
• the key churn insight section
Add them under the README using Markdown:

![Dashboard Overview](images/dashboard_overview.png)
This helps recruiters scan quickly.
Step 6: What NOT to do (very important)
Do not upload raw messy files
Do not upload multiple unfinished Tableau versions
Do not write vague README text like “this shows churn”
Do not rely on Tableau alone without explanation
What makes your project strong
You already have:
• clear business questions
• correct Tableau LOD usage
• professional insight wording
• bank-style reporting discipline
Putting it on GitHub turns this into a job-ready portfolio project, not just coursework.

If you want, next I can:
• tailor the README exactly to a Data Analyst or Risk Analyst role
• review your README text line by line
• help you choose the best project title and description for recruiters

