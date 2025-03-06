# Auto Insurance Pricing Analysis

Yoatam Gebremicael

## Project Overview
This project analyzes factors influencing auto insurance pricing in the United States using a cleaned dataset from Allstate. The goal is to identify key variables affecting insurance costs and develop statistical models to improve pricing strategies.

## Research Questions
- What are the most important factors influencing auto insurance costs?
- How do categorical factors (e.g., car type, location, policy features) impact pricing?
- Can statistical modeling improve the accuracy of cost predictions?

## Dataset
- **Source:** Allstate Insurance Dataset
- **Size:** Cleaned dataset with multiple categorical and numerical variables
- **Key Variables:** Policyholder attributes (e.g., location, car value), claim cost, and other insurance-related factors

## Methods
### 1. Data Cleaning and Preprocessing
- Converted relevant columns into categorical variables for analysis.
- Checked for missing values and handled them appropriately.
- Standardized numerical features for better model performance.

### 2. Exploratory Data Analysis (EDA)
- Visualized the distribution of insurance costs across different customer groups.
- Identified correlations between key factors and insurance pricing.
- Used box plots, histograms, and scatter plots to detect patterns in the data.

### 3. Statistical Modeling
- Applied multiple regression models to understand how variables influence insurance costs.
- Used **Statsmodels** to build and evaluate regression models.
- Tested different model specifications to assess predictive accuracy.

## Results
- Identified significant factors affecting insurance pricing, including vehicle type and geographic location.
- Found that certain policyholder characteristics strongly correlate with higher or lower claim costs.
- Regression models provided insights into cost variations and potential improvements for pricing strategies.

## Limitations
- The dataset does not account for external economic factors (e.g., inflation, regional economic differences).
- Some categorical variables may require further feature engineering for improved model accuracy.
- The analysis assumes a static pricing model, which may not fully capture real-time insurance market trends.

## How to Replicate
### Prerequisites
- Python 3.x
- Required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/auto-insurance-analysis.git
   cd auto-insurance-analysis
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis notebook in Jupyter:
   ```bash
   jupyter notebook main.ipynb
   

