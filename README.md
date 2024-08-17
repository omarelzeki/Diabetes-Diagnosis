# Diabetes Diagnosis
This project aims to diagnose diabetes using the Pima Indians Diabetes Database. The analysis and model training are performed in the `diabetes_diagnosis.ipynb` notebook.

## Dataset
The dataset used in this project is the Pima Indians Diabetes Database from Kaggle. It contains several medical predictor variables and one target variable, `Outcome`, which indicates whether a patient has diabetes.

## Project Structure
`diabetes_diagnosis.ipynb`: Jupyter notebook containing the analysis, visualizations, and model training.

## Analysis and Visualizations
The notebook includes a brief analysis of the data, including:

- Data cleaning and preprocessing
- Exploratory data analysis (EDA)
- Visualizations to understand the distribution of features and their relationships with the target variable

## Machine Learning Models
Five different machine learning classifiers are trained and evaluated in this project:

- `DecisionTreeClassifier`
- `RandomForestClassifier`
- `XGBClassifier`
- `CatBoostClassifier`
- `SVC`

## Results
The performance of each model is evaluated using appropriate metrics such as accuracy, RMSE, and F1-score. The results are compared to determine the best-performing model for diagnosing diabetes.

Installation
To run the notebook, you need to have the following libraries installed:

```shell
pip install pandas numpy matplotlib seaborn scikit-learn xgboost catboost
```
## Usage
1. Clone the repository:
```shell
git clone https://github.com/yourusername/diabetes-diagnosis.git
```
2. Navigate to the project directory:
```shell
cd diabetes-diagnosis
```
3. Open the Jupyter notebook:
```shell
jupyter notebook diabetes_diagnosis.ipynb
```
## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
