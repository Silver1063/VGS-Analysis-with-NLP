
![dataset-cover](https://github.com/user-attachments/assets/303ab5f7-ddd6-4317-8e05-6a39430cab59)

# Video Game Data Analysis
To see the full analysis, code implementation, and final prediction results, please click on the file: `vgs-data-analysis.ipynb`.
<img width="805" height="174" alt="Screenshot 2026-02-05 225805" src="https://github.com/user-attachments/assets/6888ac5c-4f33-4bab-9b21-65ad4541bf8c" />



## Project Overview
This project focuses on Predicting Nintendo Game Ratings by analyzing historical data from Metacritic. The goal is to identify patterns in professional critic scores (Meta Score) and user ratings to predict how future or imaginary titles might be received.

The analysis utilizes a dataset of Nintendo games spanning multiple generations—from the Nintendo 64 to the Switch.

## Key Features
-Data Cleaning & Preprocessing: Handling missing values, filtering out unreleased or canceled titles, and converting temporal data for analysis.

- __Feature Engineering__: Utilizing one-hot encoding for categorical variables such as game platforms and ESRB ratings.
- __Machine Learning Models__:
  - __Linear Regression__: Used as a baseline to explore the relationship between features and Meta Scores.
  - __Ensemble Methods__: Implementation of `DecisionTreeClassifier`, `BaggingClassifier`, and `RandomForestClassifier` to improve prediction accuracy and robustness.
- __Natural Language Processing (NLP)__: Leveraging `Word2Vec` (via Gensim) and PCA (Principal Component Analysis) to analyze and vectorize game titles, allowing the models to "understand" naming conventions in relation to scores.

# Results
The project culminates in a Game Score Predictor. This tool allows you to input any game name—whether it exists or is entirely made up—and receive a predicted Meta Score and User Score based on historical trends.

# Tools Used
- Language: Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, gensim
- Environment: Jupyter Notebook
