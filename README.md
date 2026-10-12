# water-potability-prediction
# Water Potability Prediction

## About the Project

This project focuses on predicting whether a water sample is potable or non-potable using machine learning. It uses different water quality parameters to train classification models and compare their performance.

The project was developed as part of the Predictive Analytics subject.

## Dataset

The project uses `water_potability.csv`, which contains water quality measurements.

The dataset includes the following features:

- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

The target column is `Potability`, where 0 represents non-potable water and 1 represents potable water according to the dataset labels.

## Tools and Libraries

- Python
- Jupyter Notebook
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Joblib

## Project Workflow

1. Understanding the dataset and its features.
2. Checking missing values and duplicate records.
3. Handling missing values using median imputation.
4. Detecting outliers using the IQR method.
5. Performing exploratory data analysis using graphs and visualizations.
6. Selecting relevant features using Mutual Information.
7. Training and evaluating machine learning models.
8. Comparing model performance using different evaluation metrics.

## Machine Learning Models

The following models are used in the project:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

The models are evaluated and compared to identify which performs best on the test dataset.

## Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

The project also includes cross-validation and other evaluation visualizations, as implemented in the notebook.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/water-potability-prediction.git
   ```

2. Open the project folder:

   ```bash
   cd water-potability-prediction
   ```

3. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost joblib jupyter
   ```

4. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open the notebook and run the cells in order. Make sure `water_potability.csv` is in the location expected by the code.

## Limitations

The predictions depend on the dataset and the performance of the trained models. The results may differ when new water samples are used.

This project is intended for educational purposes. The predictions should not be treated as confirmation that water is safe to drink. Laboratory testing is necessary to assess actual drinking water safety.

## Future Scope

The project can be improved by using more diverse data, tuning model parameters and testing the models on independent datasets.

## Author

Your Name

Predictive Analytics Project
