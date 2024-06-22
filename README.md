# Predicting-Sales-Based-on-Advertising-Spend
Project Title: Predicting Sales Based on Advertising Spend
### Background:
In today's competitive market, businesses aim to optimize their advertising budgets to maximize sales and profitability. Advertising across multiple channels such as TV, Radio, and Newspaper significantly influences consumer behavior and sales performance. However, quantifying the impact of each channel on sales remains challenging.

### Objective:
The goal of this project is to develop a predictive model to forecast sales based on spending on TV, Radio, and Newspaper advertisements. By analyzing the relationship between advertising expenditures and sales, businesses can make informed decisions on budget allocation, investing in the channels that provide the highest return on investment.

### Dataset Description:
The dataset includes:

TV: TV advertising spend (in thousands of dollars)
Radio: Radio advertising spend (in thousands of dollars)
Newspaper: Newspaper advertising spend (in thousands of dollars)
Sales: Product sales (in thousands of units)
Project Workflow:
### Loading the Dataset:
The dataset was loaded into a Pandas DataFrame for easy manipulation and analysis.

### Initial Data Exploration:
Initial exploration provided a quick understanding of the dataset's structure and content, confirming no missing values.

### Exploratory Data Analysis (EDA):

Performed statistical analyses and visualizations to understand the distribution and relationships between variables.
Found that TV advertising had a stronger correlation with sales compared to Radio and Newspaper.
Data Preprocessing:

Normalized and prepared the data for modeling.
Visualized relationships between advertising channels and sales using scatter plots and correlation matrices.
### Model Building:

Developed a linear regression model to predict sales based on advertising spend.
The model equation was derived, providing insights into the weightage of each advertising channel.
### Model Evaluation:

Evaluated the model using Mean Absolute Error (MAE) and Mean Squared Error (MSE).
The model achieved a low MAE of approximately $1,863.94, indicating accurate predictions.
### Key Insights:

TV Advertising Correlation: TV advertising showed a stronger correlation with sales compared to Radio and Newspaper.
Predictability of Advertising Spend: TV advertising spend reliably increased sales, whereas Radio and Newspaper effects were less predictable.
Model Performance: The linear regression model achieved an R-squared value of 0.89, suggesting a strong fit and significant explanatory power, especially for TV advertising.
Objective Fulfillment: The project successfully identified impactful advertising channels, providing actionable insights for marketing spend optimization. Focusing on TV advertising can lead to better sales outcomes.
