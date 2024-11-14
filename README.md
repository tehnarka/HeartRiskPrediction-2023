# Heart Risk Prediction

**Description:**
This project focuses on predicting the risk of heart disease using a Kaggle dataset. It employs regression models such as Ridge, Lasso, and ElasticNet to analyze the relationship between risk factors (e.g., age, systolic pressure) and the likelihood of heart disease. The project also includes visualizations and error analysis for model evaluation.

---

## Dataset

- **Source:** [Kaggle Heart Risk Dataset](https://www.kaggle.com/datasets/mokar20)
- **Features:**
  - `Age`: Age of the individual.
  - `Systolic`: Systolic blood pressure.
  - `Risk`: Calculated risk of heart disease.

---

## Features

1. **Data Preprocessing:**
   - Imported and cleaned data for analysis.
   - Split data into training and testing subsets.

2. **Model Implementation:**
   - Ridge Regression
   - Lasso Regression
   - ElasticNet Regression

3. **Visualizations:**
   - Scatter plots to visualize relationships between features and risk.
   - Histograms for error distribution analysis.

4. **Error Analysis:**
   - Analyzed residuals to evaluate model performance.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/HeartRiskPrediction.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python scripts:
   ```bash
   jupyter notebook
   ```

---

## Usage

1. Load the dataset:
   ```python
   df = pd.read_csv('heart_risk.csv')
   ```
2. Train the models:
   ```python
   ridge.fit(X_train, y_train)
   lasso.fit(X_train, y_train)
   elastic_net.fit(X_train, y_train)
   ```
3. Generate predictions:
   ```python
   predictions = ridge.predict(X_test)
   ```
4. Visualize results:
   ```python
   plt.scatter(df['Age'], df['Risk'])
   ```

---

## Author

- **Name:** Olha Nemkovych
- **Group:** FI-94
