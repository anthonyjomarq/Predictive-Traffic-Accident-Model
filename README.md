# Predictive Traffic Accident Model

Machine learning analysis of 2021 NHTSA traffic accident data to predict fatalities and identify accident patterns.
## Image
![alt text](<Screenshot from 2025-07-12 13-21-12.png>) ![alt text](<Screenshot from 2025-07-12 13-21-36.png>) ![alt text](<Screenshot from 2025-07-12 13-21-52.png>) ![alt text](<Screenshot from 2025-07-12 13-22-14.png>) ![alt text](<Screenshot from 2025-07-12 13-23-21.png>) ![alt text](<Screenshot from 2025-07-12 13-23-34.png>) ![alt text](<Screenshot from 2025-07-12 13-23-51.png>) ![alt text](<Screenshot from 2025-07-12 13-24-08.png>)

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
   jupyter notebook "Final_code (1).ipynb"
   ```

## Results

- **Supervised Learning**: Linear regression model with 10-fold cross-validation
- **Unsupervised Learning**: 3-cluster solution using elbow method
- **Insights**: Regional and temporal patterns in traffic fatalities

---

*University final project demonstrating data science and machine learning skills*