### Objective:
Analyze employee data to predict the likelihood of employees leaving the company (churn) using machine learning models and visualize the results in a dashboard.

### Description:
The script connects to a Google BigQuery dataset containing employee information. It uses the pycaret library to set up, train, and evaluate a classification model, specifically focusing on the "Quit_the_Company" target variable. Predictions and feature importance insights are generated, and a graphical report is created to present the results using Looker Studio. The dashboard highlights key metrics driving churn and identifies employees most at risk.

### Skills:
- Data retrieval from Google BigQuery
- Machine learning model setup and evaluation using pycaret
- Feature importance analysis
- Writing predictions and feature tables back to BigQuery
- Data visualization and reporting with Looker Studio.

### Technology:
- Python (libraries: google.cloud.bigquery, pycaret, pandas)
- Google BigQuery for data storage and retrieval
- Machine learning techniques for classification (random forest model)
- Looker Studio for data visualization and reporting.

### Results:
- Key Insights: The Random Forest model identified job satisfaction as the most critical factor in predicting employee churn. Additional important factors included tenure, the number of projects handled, average monthly hours, and performance evaluations.
- Predictions: Employees likely to leave were identified across various departments, with actionable insights provided to HR.
- Visualization: The Looker Studio dashboard presented churn by department, satisfaction levels, and other metrics, offering HR a clear view of factors driving churn and supporting the development of retention strategies.
- HR Strategy: Insights guided targeted interventions to improve job satisfaction and address systemic issues such as workload balance and career development opportunities.
