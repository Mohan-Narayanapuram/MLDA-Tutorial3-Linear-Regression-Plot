# Tutorial 3: Linear Regression and Plotting

## Overview
In this tutorial, we apply Linear Regression on the preprocessed *Medical Insurance Charges* dataset and visualize the results.

## Dataset
- **Name**: Medical Cost Personal Dataset
- **Source**: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv)  
- **Description**: Same dataset as Tutorial 1.

## Steps Performed
1. Load preprocessed training/testing data from Tutorial 1
2. Fit Linear Regression model
3. Evaluate performance (MSE, R²)
4. Plot actual vs predicted charges

## Results
- Mean Squared Error (MSE): `33,596,915.85`
- R² Score: `0.7836` (≈ 78% variance explained)

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook Tutorial-3.ipynb
```

## Credits
Dataset sourced from: [GitHub – stedy/Machine-Learning-with-R-datasets](https://github.com/stedy/Machine-Learning-with-R-datasets)  
Original dataset creator: *Stedy* (Machine Learning with R book resources)
