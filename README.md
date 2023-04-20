# A/B Testing with Kaggle Clicks Conversion Tracking Dataset
This GitHub repository contains a comprehensive A/B testing analysis using the Kaggle Clicks Conversion Tracking dataset. The goal of this project is to evaluate if targeting specific age groups leads to a higher click-through rate (CTR). The analysis includes exploratory data analysis, data cleaning, feature engineering, hypothesis testing, and effect size calculation.

## Objective
Evaluate if targeting specific age groups leads to a higher click-through rate (CTR).

### Groups:
- ages 30-34 and 35-39 vs. 40-44 and 45-49
- ages 30-34 vs. 35-39 vs. 40-44 vs. 45-49
### Metric: CTR (Clicks / Impressions)

## Dataset Overview
The dataset used for this project can be found on Kaggle: Clicks Conversion Tracking

## Analysis Steps
* Perform exploratory data analysis to understand the dataset, identify any issues, and explore the relationships between variables.
* Feature engineering to create new features such as Click-Through Rate (CTR), Cost per Click (CPC), Cost per Conversion, or Conversion Rate.
* Data cleaning to handle missing values, outliers, and ensure correct data types for each column.
* Formulate null and alternative hypotheses.
* Preprocess the data, create new variables if needed, and split the data into A and B groups based on the chosen criterion.
* Choose the appropriate statistical test and calculate the test statistic and p-value.
* Determine the significance level and make a decision to accept or reject the null hypothesis.
* Calculate the effect size and provide recommendations based on the results of the test.
* Document the work, including the analysis, code, and visualizations, in a Jupyter Notebook or a blog post.

## Repository Structure
* data/: Contains the original dataset and any processed datasets.
* notebooks/: Contains the Jupyter Notebook(s) with the analysis, code, and visualizations.
* README.md: This file, containing a summary of the project and its structure.

## How to Run the Analysis
* Clone the repository to your local machine.
* Install the required Python packages by running pip install -r requirements.txt.
* Open the Jupyter Notebook in the notebooks/ directory and run the cells in order.

## Dependencies
* Python 3.x
* pandas
* numpy
* matplotlib
* seaborn
* scipy
* sklearn
* jupyter

## Contributing
Please feel free to submit a pull request or open an issue if you have suggestions for improvements or find any bugs.

## License
This project is licensed under the MIT License.
