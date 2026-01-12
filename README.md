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
* 📁 **`notebook/`**: Contains the core Jupyter Notebook (`project_final.ipynb`) with data processing, PCA, clustering, and model validation.
* 📁 **`slides/`**: Project presentation (PDF) summarizing the methodology and financial insights for the final defense.
* 📄 **`requirements.txt`**: List of all Python libraries required to reproduce the analysis.
* 📄 **`.gitignore`**: Configuration to keep the repository clean from temporary system files.
* 📄 **`LICENSE`**: MIT License.

## 👥 Authors
* **Mardan Kydyrbek** - [GitHub Profile](https://github.com/MardanKydybek)
* **Theo Maboge** - [GitHub Profile](https://github.com/Theomab22)

**Instructor:** [@malkaguillot](https://github.com/malkaguillot)
