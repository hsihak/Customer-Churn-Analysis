# Customer Churn Analysis

## Overview
This project focuses on analyzing customer churn using Power BI, providing insights that can help businesses improve customer retention and optimize strategies. The dataset, sourced from Kaggle, includes customer demographics, activity status, and complaint history.

## Objectives
- Understand patterns and trends in customer churn.
- Provide actionable insights through dynamic dashboards.
- Equip stakeholders with data-driven recommendations for customer retention strategies.

## Key Features
- **Interactive Dashboards**: Visualize churn trends by age, gender, geography, and other critical factors.
- **Data Cleaning & Preprocessing**: Transform raw data into structured, actionable insights.
- **Insightful Analysis**: Identify the root causes of churn and opportunities for improvement.

## Tools and Technologies
- **Power BI**: For data cleaning, analysis, and visualization.
- **Dataset**: [Bank Customer Churn Dataset from Kaggle](https://www.kaggle.com/datasets).

## Project Workflow

### 1. Data Preparation
- **Removing Duplicates**: Used Power BI's "Remove Duplicates" function.
- **Column Filtering**: Removed irrelevant columns to streamline analysis.
- **Handling Missing Values**: Identified and removed rows with incomplete data.
- **Adjusting Data Types**: Corrected mismatched data types for consistency.
- **Creating New Columns**: Added calculated columns like `Age Group` for better segmentation.

### 2. Visualizations
#### Key Scenarios and Insights:
1. **Age Group with Highest Churn Rate**
   - **Visualization**: Stacked Column Chart
   - **Insight**: Customers aged `31-45` have the highest churn rate.

2. **Churn by Geography and Gender**
   - **Visualization**: Clustered Bar Chart
   - **Insight**: Region A shows the highest churn, especially among male customers.

3. **Customer Complaints**
   - **Visualization**: Pie Chart
   - **Insight**: 40% of churned customers had lodged complaints, indicating a need for improved customer service.

4. **Inactive Members**
   - **Visualization**: Grouped Bar Chart
   - **Insight**: Inactive members are twice as likely to churn compared to active members.

5. **Credit Card Ownership**
   - **Visualization**: Donut Chart
   - **Insight**: 60% of churned customers were credit card holders, highlighting potential dissatisfaction with card services.

### 3. Dashboard
The Power BI dashboard provides an intuitive, interactive interface to explore:
- Age group trends
- Regional and gender-based churn patterns
- Impact of customer complaints
- Activity level influences
- Credit card ownership and churn correlation

**Power BI Dashboard Screenshot**
![Customer_Churn_Analysis_Report conv 1](https://github.com/user-attachments/assets/b3115df6-d589-4137-817c-6e1bc44adc8f)


## Results and Recommendations
The project provides actionable insights to guide targeted interventions:
- **Age Targeting**: Focus on retention strategies for customers aged `31-45`.
- **Geographical Focus**: Implement region-specific campaigns, especially in Region A.
- **Customer Service**: Enhance complaint resolution processes to address churn drivers.
- **Re-engagement Campaigns**: Actively target inactive members with tailored offers.
- **Credit Card Services**: Revamp benefits and customer experience for cardholders.

## Repository Structure
```
Customer-Churn-Analysis/
├── Dataset/
│   └── BankCustomerChurn.csv
├── PowerBI/
│   └── CustomerChurn.pbix
├── README.md
└── Images/
    └── Customer_Churn_Analysis_Report.pdf
```

## How to Use
1. Clone the repository: `git clone https://github.com/hsihak/Customer-Churn-Analysis.git`.
2. Open the Power BI file in Power BI Desktop.
3. Explore the interactive dashboards to uncover insights.

## Future Enhancements
- **Predictive Analytics**: Integrate machine learning models to predict churn.
- **Live Data Integration**: Automate dashboard updates with real-time data.
- **Expanded Analysis**: Include more customer attributes for deeper insights.

## Contact
Hangsihak Sin  
- **Email**: hsin9104@conestogac.on.ca  
- **GitHub**: [@hsihak](https://github.com/hsihak)  

---

This project demonstrates the power of data-driven decision-making, offering a comprehensive view of customer churn dynamics. Feel free to explore the repository and reach out with any questions or feedback!
