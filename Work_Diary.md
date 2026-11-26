# Data Science Portfolio Work Diary

**Student:** Shadrach Oboh  
**Student number:** C00298390  
**Project:** Used Car Price Prediction

This diary covers the portfolio from 9 October to 26 November 2026. It is an illustrative retrospective reconstruction, not a contemporaneous log. The activities in the periods marked as illustrative are based on the project, but their dates and occurrence in those periods have not been verified. The remaining entries reflect the available notes. Periods cover five or six days, except for the shorter final period.

## 9 to 13 October 2026

On 9 October, I worked on the portfolio specification:

- Selected price prediction for used cars as a practical regression topic.
- Identified the CarDekho dataset and `selling_price` target.
- Defined research questions covering age, kilometres, fuel, transmission, seller type, important predictors, and model comparison.
- Planned Python, Pandas, Matplotlib, scikit-learn, and Jupyter as the main technologies.
- Proposed Linear Regression, Decision Tree Regression, and Random Forest Regression with MAE, RMSE, and R² evaluation.
- Submitted the portfolio specification for lecturer review.

## 14 to 19 October 2026

Illustrative reconstruction:

- Reviewed the project idea and the research questions in the portfolio specification.
- Considered how car features could be used to predict selling prices.

## 20 to 25 October 2026

Illustrative reconstruction:

- Reviewed the dataset source and the variables available for the analysis.
- Planned the notebook sections for data cleaning, visualisation and modelling.

## 26 to 31 October 2026

On 27 October, I worked on dataset acquisition, implementation and validation:

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

## 1 to 6 November 2026

On 2 November, I prepared the draft portfolio:

- Prepared a draft ZIP containing the notebook, dataset and diary.
- Created a GitHub repository for the portfolio files.

## 7 to 12 November 2026

Illustrative reconstruction:

- Reviewed the draft notebook and its explanations of the dataset and analysis.
- Considered whether the visualisations addressed the project research questions.

## 13 to 18 November 2026

Illustrative reconstruction:

- Revisited the preprocessing steps, including missing values, duplicate rows and feature engineering.
- Reviewed how the training and test data were separated before model evaluation.

## 19 to 24 November 2026

Illustrative reconstruction:

- Reviewed the regression models and compared the evaluation measures used in the notebook.
- Considered how to explain the results and limitations in the portfolio presentation.

## 25 to 26 November 2026

On 26 November:

- Reviewed the assignment brief, the notebook, the dataset and the draft submission files.
- Checked that the notebook code ran and that the data and saved results were consistent.
- Converted the notebook's assumed rupee prices to US dollars using a fixed, documented exchange rate, then reran the notebook.
- Prepared a three-slide presentation and speaker notes using the updated results.
- Updated the GitHub repository with the current notebook, presentation, requirements and a short README.
- Used AI assistance for the portfolio review, notebook changes and presentation preparation.

