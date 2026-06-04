# Statistical Distribution Analysis on Transaction Dataset

## Project Overview

This project focuses on analyzing transaction data using different statistical distributions and probability concepts.  
The analysis is performed using Python libraries such as NumPy, Pandas, SciPy, Statsmodels, Matplotlib, and Seaborn.

Dataset used in this project:

`spread_locator_dataset.csv`

---

# Part A – Theoretical Foundation

## Topics Covered

1. What is Statistical Distribution?
2. What is a Q-Q Plot and why is it used?
3. Difference between Discrete and Continuous Distributions
4. What is Bernoulli Distribution?
5. What is Binomial Distribution?
6. Explain Log-Normal Distribution
7. Explain Power Law Distribution
8. What is Box-Cox Transform?
9. Explain Poisson Distribution with an Example
10. What is Z-score Probability?
11. Difference between PDF and CDF

---

# Dataset Structure

| Field Name | Data Type | Description |
|------------|------------|-------------|
| transaction_id | UUID/String | Unique identifier for each transaction |
| customer_id | UUID/String | Unique identifier for each customer |
| transaction_amount | Float | Total amount of the transaction (₹) |
| transaction_date | Date | Date of the transaction |
| transaction_count | Integer | Number of transactions made by a customer in a given week |
| region | String | Customer’s geographic region (North, South, East, West) |
| transaction_status | String | Whether transaction was successful or failed (Success/Fail) |

---

# Part B – Practical Implementation

## Tasks Performed

### 1. Bernoulli and Binomial Distribution
- Converted transaction status into binary values
- Calculated probability of successful transactions
- Applied Binomial distribution on transaction counts

### 2. Poisson Distribution
- Modeled number of transactions occurring per day
- Calculated lambda (average transaction count)

### 3. Log-Normal and Power Law Distribution
- Fitted transaction amounts to Log-Normal distribution
- Fitted transaction amounts to Power Law distribution

### 4. Q-Q Plot Analysis
- Generated Q-Q Plot
- Tested normality of transaction amounts

### 5. Box-Cox Transformation
- Applied Box-Cox Transform
- Stabilized variance and reduced skewness

### 6. Z-score Probability
- Calculated Z-scores for transaction amounts
- Computed probability of transaction amount exceeding ₹5000

### 7. PDF and CDF Visualization
- Plotted Probability Density Function (PDF)
- Plotted Cumulative Distribution Function (CDF)

### 8. Final Conclusion
- Compared distributions
- Identified best fitting distribution for dataset

---

# Python Libraries Used

```python
numpy
pandas
scipy
statsmodels
matplotlib
seaborn
