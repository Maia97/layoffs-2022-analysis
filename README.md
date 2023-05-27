# Predicting Tech Sector Layoffs Using Time Series Analysis

## Project Overview

This project analyzes data related to layoffs in the tech industry. It seeks to answer some crucial questions, providing valuable insights that can help businesses, job seekers, and policymakers to better understand the industry trends, especially amid uncertain economic times.

**Key Questions:**

1. Which industries within the tech sector are experiencing the most significant impact from layoffs?
2. In which geographic regions are companies with high layoff ratios predominantly located?
3. What is the financing status of the layoff companies?
4. What is the relationship between the financing status of companies and the percentage of layoffs they have experienced?
5. Has the wave of layoffs reached its peak, or is it still ongoing, what are the potential future trends of the layoff wave?

## Installation

Python 3.7.12 is required along with the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scipy`
- `statsmodels`
- `pmdarima`

To install these libraries, you can use the command: `pip install -r requirements.txt`

## Files in the Repository

1. `README.md`: Provides a discussion on the motivation for the project, libraries used, files in the repository with a small description, and a summary of the results.

2. `layoffs-2022-analysis.ipynb`: This Jupyter notebook contains all the Python code used for the analysis. It is well-documented with comments, analysis, and visualizations.

3. `layoffs.csv`: This is the dataset used for this analysis. The dataset, which includes daily layoffs from different tech companies, can be downloaded from [here](https://www.kaggle.com/datasets/swaptr/layoffs-2022).

## Results Summary

Our analysis revealed several crucial findings in response to our initial questions:

1. **Industries Impacted:** Consumer, Retail, Transportation, Other, Finance, Real Estate, Healthcare, Food, Security, and Marketing.

2. **Geographic Distribution:** top 5 tech hubs in the U.S., SF Bay Area, New York City, Boston, Los Angeles, and Seattle.

3. **Financing Status:** generally early stage, from Series A to B, or with fundings less than $100M.

4. **Financing Status vs. Layoffs:** a significant negative relationship between the percentage laid off and funds raised.

5. **Layoff Trends:** predictions suggest that layoffs will continue but with less volatility. 

For a more detailed discussion of these findings, please visit our [blog post](https://medium.com/@yg2483/navigating-the-wave-understanding-the-trends-and-impacts-of-layoffs-in-the-tech-industry-38916908041e).


## License and Acknowledgments

This project is licensed under the terms of the MIT license.

Data for this project was sourced from [Kaggle](https://www.kaggle.com/datasets/swaptr/layoffs-2022). We appreciate and acknowledge the providers of this dataset for making this valuable information available for public use.
