# Telecom-Churn-Analysis-and-Visualization-and-Prediction-Model
# Customer Churn Analysis and Prediction

## Overview
Customer churn is a critical issue for businesses, especially in the telecommunications industry. This project focuses on analyzing customer behavior to identify patterns that indicate churn and building predictive models to help mitigate customer loss. By leveraging machine learning and data analysis techniques, the goal is to provide actionable insights for improving customer retention strategies.

## Dataset
The dataset contains information about customer demographics, account details, service usage, and whether the customer has churned. Key attributes include:
- **CustomerID**: Unique identifier for each customer.
- **Tenure**: Duration of customer relationship.
- **Contract Type**: Monthly, one-year, or two-year contract.
- **Payment Method**: Type of payment method used.
- **Monthly Charges**: Amount billed monthly.
- **Total Charges**: Total amount billed.
- **Churn**: Whether the customer has left (Yes/No).

## Objectives
- Perform **Exploratory Data Analysis (EDA)** to understand key trends.
- Identify **factors influencing churn** using statistical analysis.
- Develop **predictive models** to classify churners vs. non-churners.
- Provide **actionable insights** to reduce churn and improve retention.

## Methodology
1. **Data Preprocessing**: Handle missing values, data transformation, and feature engineering.
2. **Exploratory Data Analysis (EDA)**: Visualize trends, correlations, and customer behavior.
3. **Feature Selection**: Identify the most significant factors affecting churn.
4. **Model Training & Evaluation**: Compare classification models such as:
   - Logistic Regression (Accuracy: **0.8009950248756219**)
   - Gradient Boosting (XGBoost) (Accuracy: **0.8038379530916845**)
   - AdaBoost Classifier (Accuracy: **0.8109452736318408**)
5. **Model Performance Analysis**: Evaluate models using accuracy, precision, recall, F1-score, and AUC-ROC.
6. **Final Accuracy Score**: **0.8052594171997157**
7. **Business Recommendations**: Suggest strategies to minimize churn based on insights.

## Results & Insights
- High churn is observed among **monthly contract customers** with **high monthly charges**.
- Customers using **electronic check payments** are more likely to churn.
- Long-tenure customers have **higher retention rates**.
- The **Random Forest model** provided the best accuracy in predicting churn.

## Churn Prediction Example
Using the trained model, churn probabilities were predicted for multiple sample customers:

```
Customer 1: 🔮 Churn Probability = 0.6975
   🔴 Likely to churn.
Customer 2: 🔮 Churn Probability = 0.4699
   🟢 Not likely to churn.
Customer 3: 🔮 Churn Probability = 0.3415
   🟢 Not likely to churn.
Customer 4: 🔮 Churn Probability = 0.5826
   🔴 Likely to churn.
```

**Interpretation:**
- Probabilities **close to 0** indicate that the customer is **not likely to churn**.
- Probabilities **close to 1** indicate that the customer is **likely to churn**.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost,Plotly
- **Tools**: Jupyter Notebook, GitHub

## Future Improvements
- Incorporate **deep learning models** for improved predictions.
- Use **customer feedback sentiment analysis** for better insights.
- Implement **real-time churn prediction** for proactive retention strategies.

## Conclusion
This project demonstrates the importance of data-driven decision-making in customer retention. By identifying key churn factors and leveraging predictive analytics, businesses can proactively engage with at-risk customers and reduce churn rates.





