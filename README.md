MARKETING ROI ANALYSIS 
                    Project Overview
This project analyzes the relationship between advertising expenditure and sales performance using Simple Linear Regression. The goal is to understand how TV advertising spending influences sales and to evaluate its effectiveness in driving Return on Investment (ROI).
The dataset includes advertising expenditure across TV, Radio, and Social Media, along with corresponding sales data. However, the regression model focuses on TV advertising as the independent variable and sales as the dependent variable.
**Objective**
To examine the relationship between TV advertising and sales
To build a simple linear regression model
To evaluate model performance using R² and statistical significance
To provide business insights for marketing budget allocation
**Repository Structur**e
Marketing-analysis/
├── regression_analysis.ipynb # Main Jupyter Notebook (fully executed)
├── README.md # Project documentation
**Environment Setup**
To run this project, install the required dependencies:
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
**How to Run the Project**
Clone the repository:
git clone https://github.com/osfranko/Marketing-analysis.git
Navigate to the project folder:
cd Marketing-analysis
Launch Jupyter Notebook:
jupyter notebook
Open and run:
regression_analysis.ipynb
        **Business Interpretation**

The regression analysis shows that TV advertising has a very strong positive relationship with sales performance.

The model achieved an R-squared value of 0.99, indicating that approximately 99% of the variation in sales is explained by TV advertising expenditure alone.

The coefficient for TV advertising is positive and statistically significant, meaning that increases in TV advertising spending lead to higher sales.

Diagnostic plots indicate that the assumptions of simple linear regression (linearity, normality of residuals, and homoscedasticity) are reasonably satisfied, supporting the validity of the model.
         **ROI Recommendation**

Based on the regression results, TV advertising should be prioritized as the most effective marketing channel.

The analysis shows that TV advertising has a strong and reliable impact on sales and provides a clear return on investment.

Therefore, management should allocate a larger portion of the marketing budget to TV advertising campaigns in order to maximize sales growth and overall ROI.
Tools & Libraries Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Statsmodels
Jupyter Notebook
    AUTHOR osemwengie osasere 
