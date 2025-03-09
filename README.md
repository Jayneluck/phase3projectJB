# SyriaTel Customer churn and retention analysis
Author : Jane Bahati
## Business Understanding
Customer retention is a major challenge in the telecommunications industry, where companies operate in a competitive market with numerous service providers. High customer churn rates lead to revenue loss, increased customer acquisition costs, and reduced market share. By understanding churn patterns, telecom companies can take proactive measures to retain customers and improve satisfaction.
## Problem statement
SyriaTel, a leading telecom provider, seeks to minimize customer churn by identifying key factors influencing customer departure. Using data on call usage, billing history, international plan subscriptions, and customer service interactions
## Objectives
The goal is to develop a binary classification model to predict customer churn (Churn vs. No Churn) by leveraging customer behavior, call patterns, and billing data. Key predictive features will be extracted to enhance model performance through feature selection, hyperparameter tuning, and class balancing. Various models, including Logistic Regression, Decision Trees, and Random Forest, will be compared to determine the most effective approach. Performance will be evaluated using classification metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
## Results
Customer churn vs customer service calls
![image](https://github.com/user-attachments/assets/61ece19b-2871-4941-b18b-5d38910ee464)
## Customer service calls; churned vs retained customer
![image](https://github.com/user-attachments/assets/ed9fb4d1-9e29-4cbc-a58e-de40c15de1c3)

## Observations
The Tuned Random Forest emerged as the best model, achieving the highest AUC-ROC and F1 Score, indicating superior classification performance and balance between precision and recall. Random Forest models outperformed Decision Trees, highlighting the strength of ensemble learning, while hyperparameter tuning significantly improved results. Logistic Regression performed reasonably but was outshined by non-linear models. AUC-ROC was a key metric, reflecting the models' ability to distinguish between classes, while lower log loss indicated better probability calibration. Overall, tuned Random Forest is the optimal choice, and further improvements could involve feature engineering or advanced ensemble techniques.
## Conclusion
Multiple machine learning models were developed to predict customer churn for SyriaTel, with Random Forest achieving the best performance across key metrics. The analysis identified factors like call usage, billing history, international plan subscriptions, and customer service interactions as major churn indicators. Customers with frequent service calls, higher call charges, or international plans were more likely to churn.
## Recommendation
To reduce churn, SyriaTel should improve customer service, offer personalized discounts, and use its churn model to engage at-risk customers proactively. Enhancing billing transparency and flexible pricing can also reduce dissatisfaction. Continuous model monitoring will ensure accuracy and adaptability. These strategies will boost retention, satisfaction, and revenue.
## For more information
See the full analysis in the notebook https://github.com/Jayneluck/phase3projectJB/blob/main/notebook.pdfx.pdf or review this presentation contact information Jaynembahati@gmail.com
