# Loan Risk Prediction - Exploratory Data Analysis (EDA)

## Project Overview
This project involves performing Exploratory Data Analysis (EDA) on loan application data to derive insights and understand patterns in customer profiles and loan defaults. By analyzing and visualizing the data, we can gain meaningful insights into the risk of loan defaults based on various factors such as income, occupation, credit amount, and more. The analysis will help financial institutions target customers effectively and make informed decisions when issuing loans.

## Key Features
- **Data Cleaning & Preprocessing**: Handled missing values and reduced the dataset to relevant features.
- **Visualization**: Created informative visualizations using Seaborn and Plotly to highlight key financial variables and trends.
- **Correlation Analysis**: Identified correlations between customer features and loan default rates.
- **Customer Segmentation**: Classified customers based on risk profiles and provided actionable insights.

## Insights Derived
- **Loan Default Patterns**: 
  - Customers with lower incomes (<1 million) are more likely to default, especially when their loan amounts are greater than 1.5 million.
  - Females generally have a lower default rate (~7%), making them a safer segment to lend to.
  - Higher education correlates with a reduced likelihood of default (less than 5%).
  - Occupations such as accountants and managers are less likely to default, while low-skill laborers and drivers are at higher risk.
  
- **Actionable Segments**:
  - Customers working in certain business sectors, such as "Others" and "Business Entity Type 3," are safe to target for loans.
  - Unaccompanied people have a relatively low default rate (~8.5%).
  - Married people, particularly those with 1-5 children, are safer to lend to.

## Visualizations
Some of the visualizations include:
- Distribution of loan amounts and goods prices.
- Heatmap showing correlation between different financial variables.
- Bar plots and histograms to understand the spread of income, credit amount, and annuity across different customer groups.

## Technologies Used
- **Python**: Main programming language used.
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Matplotlib/Seaborn/Plotly**: For data visualization.
- **Jupyter Notebooks**: For running and documenting the analysis.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/salahradwan2210/EDA.git
   cd EDA
