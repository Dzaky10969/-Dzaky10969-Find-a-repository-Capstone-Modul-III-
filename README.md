# -Dzaky10969-Find-a-repository-Capstone-Modul-III-
Modeling Data Bank Marketing Campaign ,dibuat untuk memenuhi Capstone Modul II

Bank Marketing Campaign - Predictive Modeling
Project Overview
This project aims to build a predictive model to assist Bank ABC in improving the efficiency and effectiveness of its term deposit marketing campaigns. The project utilizes a dataset of previous marketing campaigns to develop a model that predicts which customers are most likely to subscribe to a term deposit. The final model provides key insights into customer behavior and optimizes marketing efforts by minimizing wasted resources and maximizing potential profits.

Goals:
Improve Marketing Efficiency: Reduce marketing costs by identifying customers who are less likely to accept deposit offers.
Optimize Resource Allocation: Focus marketing efforts on high-potential customers to maximize conversion rates.
Increase Campaign Success: Provide actionable insights to improve the effectiveness of the bank's marketing strategy.
Dataset
The dataset used in this project consists of customer information and campaign results. Key features include:

Demographic Data: Age, job, housing status, loan status, etc.
Campaign Information: Number of contacts, previous campaign outcomes, and the date of contact.
Behavioral Data: Balances, previous deposits, and related financial activities.
Methodology:
1. Data Preprocessing
Data was cleaned, missing values were handled, and relevant features were encoded.
Feature selection techniques were used to focus on the most impactful variables.
2. Modeling
Random Forest Classifier with hyperparameter tuning and threshold adjustments was used to create the final model.
A baseline Rule-Based approach was also implemented for comparison.
The final Random Forest model provided superior performance with an f1-score of 0.68 compared to 0.49 from the rule-based approach.
3. Evaluation
Key business metrics were evaluated, such as True Positives (correctly predicted deposits) and False Negatives (missed opportunities).
Business outcomes were compared between the model-based approach and the rule-based approach, showing a significant increase in potential revenue using the Random Forest model.
Key Results
Random Forest Classification:
f1-score: 0.68
Revenue Opportunity: Potential revenue increase of Rp3.648.960.000, a 376% improvement compared to the rule-based method.
Reduction in Opportunity Cost: 45.83% reduction in potential lost revenue due to false negatives.
Business Recommendations:
Implement the Random Forest Model for future campaigns to optimize marketing efforts.
Focus marketing on customers with characteristics identified as high potential by the model, such as previous successful campaign results, high balance, and no loan status.
