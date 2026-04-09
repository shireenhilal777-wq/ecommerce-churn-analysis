# E-commerce Customer Churn Analysis
This project identifies why customers are leaving an e-commerce platform and predicts future churn using Python.

## The Goal
The objective is to analyze customer behavior (order frequency, tenure, and complaints) to provide actionable insights for the marketing team.

## Tech Stack
- **Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, Scikit-learn
- **Tools:** Jupyter Notebook / Google Colab

## Project Structure
- `data/`: Contains the raw dataset.
- `notebooks/`: Exploratory Data Analysis (EDA) and Model building.
- `visuals/`: Charts showing churn trends.

# Executive Summary: Churn Analysis Findings
The Objective:
To determine if customer demographics (Age, Income, Gender) and spending behavior could accurately predict customer churn.

## Key Technical Insights:
- Feature Correlation: Initial EDA revealed a "weak correlation" across all primary features.  A heatmap analysis confirmed that no single factor—such as Annual Income or Spending Score—directly drives a customer to leave.

- Model Performance: A Decision Tree Classifier achieved 66.25% accuracy. While this provides a baseline, it performs similarly to the majority class baseline (69%), suggesting that churn in this dataset is likely driven by external factors not captured in the current variables.

- Top Predictor: The model identified Membership Years as the most significant splitting factor, though its predictive power remains limited by the high variance in the data.

## Strategic Recommendations:
- Data Expansion: Since demographic data proved inconclusive, the company should begin collecting behavioral data, such as customer service interaction frequency, app session length, and last login date.
 
- Unbiased Churn: Because churn is uniform across all age groups and income levels, retention marketing should be broad-based rather than targeted at a specific demographic segment.
