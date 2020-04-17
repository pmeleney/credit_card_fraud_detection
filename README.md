# Credit Card Fraud as Outlier Detection

## Introduction
In 2018 US credit card companies lost \$9.36B to fraud, the highest reported loss for any country in the world.  Identifying credit card fraud is essential for protecting customers and companies.  Companies with lower rates of fraud can protect earnings and pass savings on to customers, potentially leveraging a market advantage.

In 2018 Machine Learning Group - ULB provided a data set on Kaggle which contained transactions made by credit card over two days in September 2013 by European cardholders.  The objective of the exercise is to identify as many of the 492 frauds as possible, while excluding the 284,315 legitimate transactions.

I will approach this problem as outlier identification.  The implicit hypothesis is that fraudulent purchases are dissimilar to "regular" non-fraudulent purchasing habits, and therefore constitute a disproportionate number of the outliers.  The advantage of this approach is that we will not need to exclude data or "balance" the highly unbalanced data set, we will identify and flag outliers directly which, by their nature, constitute a small percentage of examples.

For a more complete report see Credit_Card_Fraud_as_Outlier_Detection.pdf.
