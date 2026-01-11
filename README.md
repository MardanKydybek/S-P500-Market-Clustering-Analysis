# S&P 500 Market Clustering & Behavioral Analysis

## Project Overview
This project uses Unsupervised and Supervised Machine Learning to identify hidden structures in the S&P 500 market. By clustering stocks based on historical price behavior, we identify distinct risk-return profiles for advanced portfolio diversification.

## Methodology
* **Data Retrieval:** Automated fetching of S&P 500 data using `yfinance`.
* **Dimensionality Reduction:** PCA implementation to retain 10 principal components (90% variance).
* **Unsupervised Learning:** K-Means clustering with optimal $K=7$ identified via the Elbow Method.
* **Supervised Validation:** Comparison of **Logistic Regression** and **Random Forest** to validate cluster stability.

## Key Results
* **Clustering:** Successfully identified 7 behavioral stock groups.
* **Validation Accuracy:** * Logistic Regression: **85%**
  * Random Forest: **80%**
* The high accuracy confirms that the market clusters are statistically significant and non-random.

## Structure
* `notebook/`: Contains the main Jupyter Notebook (`project_final.ipynb`) with full analysis.
* `requirements.txt`: List of necessary Python libraries.

**Authors:** Theo Maboge, Mardan Kydyrbek
**Professor:** @malkaguillot
