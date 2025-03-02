# Airlines_Profit_Prediction
To predict airline profitability and provide actionable insights for operational optimization.


# Aviation Profit Prediction Using Machine Learning

## Problem Statement

Airlines operate in a highly competitive industry where profitability is influenced by various factors, including revenue, operating costs, and market conditions. The goal of this project is to develop a machine learning model that predicts airline profit based on key business performance indicators (KPIs). By analyzing historical data and identifying trends, this model can help airlines optimize operations and improve financial performance.

## Dataset Overview

The dataset used in this project contains aviation key performance indicators (KPIs) such as:

- *Revenue (USD)*
- *Operating Cost (USD)*
- *Profit (USD)*
- Other business metrics relevant to airline performance

## Data Preprocessing

1. *Data Cleaning:*
   - Checked for missing values (none found).
   - Standardized column names for consistency.
2. *Outlier Detection and Removal:*
   - Visualized outliers using boxplots.
   - Removed extreme outliers to ensure better model performance.
3. *Feature Engineering:*
   - Applied one-hot encoding to categorical features.
   - Analyzed feature correlation with profit using heatmaps and scatterplots.
  
4. ## Exploratory Data Analysis (EDA)

- *Visualized the distribution of profit* to understand its spread.
- *Created correlation heatmaps* to analyze relationships between revenue, cost, and profit.
- *Generated scatter plots and histograms* to inspect feature distributions and patterns.

## Model Training

- *Splitting the Data:*
  - 60% for training.
  - 20% for validation (to check overfitting).
  - 10% for testing.
  - 10% for additional testing.
- *Random Forest Model:*
  - Trained a Random Forest Regressor on the processed dataset.
  - Tuned hyperparameters to optimize performance.

## Model Evaluation

- *R² Score (Coefficient of Determination):* Measures how well the model explains variance in profit.
- *Root Mean Squared Error (RMSE):* Evaluates prediction accuracy.
- *Validation vs. Test Performance:* Ensured no overfitting.

## Deployment

- The trained model can be integrated into business decision-making tools for real-time profit prediction.
- Future improvements could include:
  - Feature selection refinement.
  - Experimenting with other algorithms like XGBoost.
  - Enhancing model interpretability.

## How to Use

1. Clone the repository:
   sh
   git clone <repo-url>
   
2. Install dependencies:
   sh
   pip install -r requirements.txt
   
3. Run the model:
   sh
   python train_model.py
   
4. Evaluate results:
   sh
   python evaluate_model.py
## Conclusion

This project successfully developed a *profit prediction model* for the airline industry using *Random Forest Regression*. The model provides valuable insights into revenue and cost impacts on profit, enabling airlines to make data-driven financial decisions.




## [Here is the Explanation vidio of the code](https://drive.google.com/file/d/1v2kbquOMaSwWQvuh-imlvJAJ4FeKUFsL/view?usp=drive_link)
## we r not able to upload the trained model due to the uplode size ristrictions on github so ve r uploading all remaining dataset files and trained model on drive u can access is [HERE](https://drive.google.com/drive/folders/1ersXZP54o-5GyV1lAyjWyjEkWpAj2Y1q?usp=drive_link)
