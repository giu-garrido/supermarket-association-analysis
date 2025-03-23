# 🛒 Supermarket Association Analysis (Manual Apriori Implementation)

This repository contains the implementation of the **Apriori algorithm** for **association rule mining** on supermarket transaction data. The algorithm was implemented manually without using the `mlxtend` library or other specialized packages, allowing a deeper understanding of the algorithm's inner workings.

## 📋 Project Structure:
- **data/**: Contains the dataset used for analysis.
- **notebooks/**: Jupyter/Colab notebooks with data preprocessing, implementation of the Apriori algorithm, and analysis of results.

## 📊 Metrics used:
- **Support**: Frequency of item occurrence in the dataset.
- **Confidence**: Probability of item B being purchased when item A is purchased.
- **Lift**: Measure of the strength of association between item A and B.
- **Conviction**: Indicates how strongly the purchase of A predicts the purchase of B.
