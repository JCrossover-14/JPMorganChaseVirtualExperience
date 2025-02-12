# JP Morgan Chase Quantitative Research Program

This repository contains solutions to four quantitative research tasks provided by the JP Morgan Chase Quantitative Research Program. The project focuses on financial and energy market modeling using statistical and machine learning techniques.

# Tasks

1. Gas Price Prediction

- Utilizes a Seasonal AutoRegressive Integrated Moving Average (SARIMA) model

- Predicts future gas prices based on two years of historical gas data

- Evaluates model accuracy and performance with statistical metrics

2. Gas Contract Pricing Model

- Develops a pricing model for gas contracts using the gas price predictions

- Factors considered in pricing:

  - Injection dates

  - Withdrawal dates

  - Injection rates

  - Injection and withdrawal costs

  - Maximum storage volume

  - Storage cost per month

3. Loan Default Prediction

- Uses logistic regression to predict customer loan defaults

- Features include customer credit scores and financial history

- Evaluates model accuracy with performance metrics

4. Customer Risk Categorization

- Applies dynamic programming to categorize users based on their FICO scores

- Generates categorical labels to classify users by their likelihood of default

- Optimizes classification for risk assessment and lending decisions


# Usage

Each task has its own directory with relevant scripts and Jupyter notebooks. Navigate to the appropriate folder and run the corresponding notebook to reproduce the results.

# To-Do

- Example solution just uses simple sinsuidal curve fitting vs a time series forecast. Perhaps that is better?
- Maybe there is a better DP approach in Task 4. Current time complexity is ~(n^2 log(n))

Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests.
