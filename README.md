# Marketing Analytics Project

## Description
This project investigates customer behaviors and purchasing patterns to guide marketing strategies, focusing on customer segmentation, churn prediction, and product association. Models include RFM analysis, churn prediction models (e.g., Random Forest, Logistic Regression), and market basket analysis to identify potential upsell and cross-sell opportunities.

## Business Questions

- How can marketing efforts be personalized based on customer purchasing behaviors?
- How can at-risk customers be proactively identified to improve retention?
- What product combinations can enhance sales and customer satisfaction?
- What is the likelihood of customer churn based on historical behaviors?

## Target Clients

- By Age: The focus is on individuals aged 35-50.
- By Region: Primary customer base is in northern and central Italy.
- By Purchase Patterns: High frequency of repurchases within the first 10 days.

## Pipelines Used

- Data Exploration:
Regional distribution and purchase patterns by frequency.
Analysis of customer engagement based on product reviews.
- Modeling:
  - RFM (Recency, Frequency, Monetary) Analysis: Segments customers based on transactional behavior.
  - Churn Models: Logistic Regression, Multilayer Perceptron, and Random Forest.
  - Clustering: K-Means clustering with PCA for customer grouping.
  - Market Basket Analysis: Apriori algorithm for product association rules.


## Model Evaluation Pipeline

- RFM Analysis: Identifies high-value customers for targeted marketing.
- Churn Analysis: Logistic Regression and Multilayer Perceptron with AUC comparison; Random Forest showed the highest accuracy.
- Market Basket Analysis: Key associations identified for cross-selling.

## Key Findings

- Customer Insights: RFM identified valuable customer segments, while churn analysis highlighted high-risk groups.
- Product Associations: Basket analysis revealed influential product combinations.
- Regional Trends: Marketing efforts can be optimized for high-density regions in Italy.

## Future Work

- Extend the dataset to capture longer-term trends.
- Explore advanced machine learning techniques (e.g., deep learning) for improved predictive accuracy.
- Integrate real-time data streams for ongoing customer insights.