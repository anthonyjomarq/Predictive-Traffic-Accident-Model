# Predictive Traffic Accident Model

Machine learning analysis of 2021 NHTSA traffic accident data to predict fatalities and identify accident patterns.
## Visualizations
![Distribution by Time of Day](images/Screenshot%20from%202025-07-12%2013-21-12.png) 
![Distribution by Day of Week](images/Screenshot%20from%202025-07-12%2013-21-36.png) 
![Age Group Analysis](images/Screenshot%20from%202025-07-12%2013-21-52.png) 
![Vehicle Type Distribution](images/Screenshot%20from%202025-07-12%2013-22-14.png) 
![Fatalities Distribution](images/Screenshot%20from%202025-07-12%2013-23-21.png) 
![BAC Test Results](images/Screenshot%20from%202025-07-12%2013-23-34.png) 
![Cross-Validation Results](images/Screenshot%20from%202025-07-12%2013-23-51.png) 
![K-Means Clustering](images/Screenshot%20from%202025-07-12%2013-24-08.png)

## Overview

- **Predicts fatalities** in traffic accidents using Linear Regression
- **Clusters accident patterns** using K-means clustering  
- **Analyzes 198,458 accident records** from FARS 2021 dataset

## Key Findings

- Time patterns show peak accident periods
- Certain age groups have higher fatal accident rates
- Regional differences in accident severity
- Vehicle type correlations with fatality rates

## Technologies

- Python, Pandas, Scikit-learn
- Matplotlib, Seaborn for visualization
- Jupyter Notebook

## Setup

1. Install dependencies:
   ```bash
   pip install pandas scikit-learn matplotlib seaborn numpy scipy
   ```

2. Download FARS 2021 data from [NHTSA](https://www.nhtsa.gov/research-data/fatality-analysis-reporting-system-fars)

3. Place data files in `datasets/` folder:
   - ACC_AUX.CSV
   - VEH_AUX.CSV  
   - PER_AUX.CSV

4. Run the notebook:
   ```bash
   jupyter notebook Traffic_Accident_Analysis.ipynb
   ```

## Results

- **Supervised Learning**: Linear regression model with 10-fold cross-validation
- **Unsupervised Learning**: 3-cluster solution using elbow method
- **Insights**: Regional and temporal patterns in traffic fatalities

---

*University final project demonstrating data science and machine learning skills*