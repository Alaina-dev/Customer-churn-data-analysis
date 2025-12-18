# Customer-churn-data-analysis  ![tableau_label](images/tableau_label.png)
This Tableau project explores customer churn behaviour for exploratory data analysis (EDA)using customer geograph and service interaction data. It focuses on identifying early churn indicators through analysis of interaction frequency, interaction type, resolution status, and recency of the final customer interaction.

## Interactive Dashboard
[View Interactive Tableau Dashboard:](https://public.tableau.com/views/Bankcustomerchurndataanalysis/CustomerServiceResolution?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Tools and Technologies
Tableau Desktop Public Edition version 2025.2.4
Microsoft Excel

## Dataset Description
The dataset is sourced from the Lloyds Banking Group Virtual Experience programme on Forage and is organised across multiple tables, including Customer_Demographics, Transaction_History, Customer_Service, Online_Activity, and Churn_Status. Together, these tables contain anonymised customer segmentation, customer service interaction, and behavioural data, including catogories like interaction type, resolution status, and interaction dates.

## Data Preparation
Data cleaning and preparation were carried out using Excel and Python (Google Colab). This process included validation of categorical fields, detection of outliers in numerical variables such as age and transaction amounts, handling missing values, removal of duplicate records, and correction of data types. The detailed data cleaning workflow and code are documented in a separate repository, available here: 🧹 [Data Cleaning Repository](https://github.com/Alaina-dev/Data-cleaning-Customer-churn-data-analysis). 

Additional features were created during the analysis phase in Tableau, including derived metrics such as interaction frequency per customer and recency of the last interaction..
### Calculated Fields Summary

## Analysis Overview
The analysis focuses on:
• Churn rate by interaction type
• Complaint frequency and resolution outcomes
• Repeated interactions and service fatigue
• Recency of last interaction as an early churn signal
### Dashboards
![Customer_Demographics_Overview](images/Customer_Demographics_Overview.png)
![Customer_Segmentation_Churn_Status](images/Customer_Segmentation_Churn_Status.png)
![Transaction_Behaviour_Churn_rate](images/Transaction_Behaviour_Churn_rate.png)
![Cusomter_Service_Interactions_Churn_Risk](images/Cusomter_Service_Interactions_Churn_Risk.png)
![CustomerComplaints_Churn](images/CustomerComplaints_Churn.png)
![Online_Activity_Engagement](images/Online_Activity_Engagement.png)

Customer-level metrics were created using Tableau LOD calculations to ensure accurate aggregation.

### Key Insights
Customers with repeated service interactions show higher churn risk, particularly when issues remain unresolved. Complaint-related interactions are disproportionately represented among churned customers, while prolonged inactivity following an unresolved final interaction strongly indicates disengagement.

## Full Report
For a detailed methodology, analysis, and interpretation of results, see the full report here:  
📄 [Download the full analysis report (PDF)](reports/Customer_churn_data_analysis_report.pdf)

## Future Work
This dataset could be extended into predictive modelling by encoding categorical variables and scaling numerical features for machine-learning algorithms.
