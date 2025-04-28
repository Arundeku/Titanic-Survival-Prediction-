# Titanic Survival Prediction 🚢

## Project Overview
This project aims to predict passenger survival from the Titanic disaster using machine learning techniques.  
The dataset comes from the famous Kaggle Titanic competition.

We performed:
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Building a Decision Tree Classifier
- Model Evaluation
- Submission File Creation

## Files
- `train.csv` — Training dataset (provided)
- `test.csv` — Test dataset (provided)
- `gender_submission.csv` — Example submission file
- `Titanic_Survival_Prediction_Report.docx` — Detailed final project report
- `submission.csv` — Our model's predictions for the test set

## Project Structure
- **EDA**: Understanding the data and survival patterns.
- **Preprocessing**: Cleaning data (handling missing values, encoding categorical variables).
- **Model Building**: Decision Tree Classifier for predicting survival.
- **Evaluation**: Accuracy measured with training data and cross-validation.

## How to Run
1. Install necessary Python libraries (if not already installed):
   ```bash
   pip install pandas scikit-learn matplotlib seaborn
   ```
2. Open and run the Jupyter Notebook / Python script.
3. Load the training and test datasets.
4. Train the model and generate predictions.
5. Create the `submission.csv` file for evaluation.

## Model Performance
- Training Accuracy: **~98%**
- Cross-Validation Accuracy: **~79%**

*Note*: Decision Tree shows some overfitting; further improvement is possible with feature engineering and model tuning.

## Future Improvements
- Feature engineering (e.g., extracting titles from names).
- Using more advanced models like Random Forests or XGBoost.
- Hyperparameter tuning to reduce overfitting.

## Credits
- Dataset: [Kaggle Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
