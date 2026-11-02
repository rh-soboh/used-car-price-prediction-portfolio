# Data Science Portfolio Work Diary

**Student:** Shadrach Oboh  
**Student number:** C00298390  
**Project:** Used Car Price Prediction

This diary records the development of the portfolio. Entries distinguish completed work from planned work so that the log remains accurate.

## Completed entries

### 9 October 2026: Portfolio specification

- Selected price prediction for used cars as a practical regression topic.
- Identified the CarDekho dataset and `selling_price` target.
- Defined research questions covering age, kilometres, fuel, transmission, seller type, important predictors, and model comparison.
- Planned Python, Pandas, Matplotlib, scikit-learn, and Jupyter as the main technologies.
- Proposed Linear Regression, Decision Tree Regression, and Random Forest Regression with MAE, RMSE, and R² evaluation.
- Submitted the portfolio specification for lecturer review.

### 27 October 2026: Dataset acquisition, implementation, and validation

- Downloaded `Car details v3.csv` from the Vehicle Dataset from CarDekho Kaggle page.
- Verified the expected 8,128 rows and 13 columns.
- Set up an isolated Python virtual environment and recorded package versions.
- Audited data types, missing values, category values, numerical summaries, and 1,202 exact duplicate rows.
- Removed exact duplicates before splitting to reduce train/test leakage risk.
- Engineered car age, brand, numeric mileage, mileage unit, engine displacement, maximum power, and torque in Nm.
- Created exploratory visualisations for the price distribution, age, kilometres driven, fuel, transmission, seller type, brands, and correlations.
- Built preprocessing pipelines where imputation, scaling, and category encoding are fitted only to training data.
- Trained and compared a median reference, Linear Regression, Decision Tree, and Random Forest.
- Used validation across five training folds and a separate 20% test set.
- Added plots for actual and predicted prices, residuals, and feature importance.
- Executed the notebook from a clean kernel and exported it to HTML for submission/reading.



## Planned next steps


- Add professional LinkedIn, GitHub, or website links if available.
- Run the complete notebook again after any changes and confirm that all cells execute in order.
- Practise the presentation and add a diary entry recording feedback or revisions.
