# Marketing & Sales Prediction | Linear & Regularized Regression

**A machine learning project exploring sales prediction using Linear Regression, Ridge, Lasso, and ElasticNet.**

## 📌 Project Overview

This project explores how marketing investments, discounts, website traffic, conversion rates, and customer or product attributes relate to sales.

The project begins with a baseline Linear Regression model, examines key regression assumptions, and then investigates whether regularization techniques improve predictive performance, coefficient stability, and interpretability.

## 🎯 Objectives

- Build a baseline Linear Regression model to predict sales.
- Understand relationships between marketing variables and sales.
- Examine regression assumptions and model coefficients.
- Implement Ridge, Lasso, and ElasticNet regression.
- Apply K-Fold cross-validation to tune model hyperparameters.
- Compare models using regression evaluation metrics.
- Select a final model based on cross-validation and test-set performance.

## 📂 Project Files

| Resource | Description |
|---|---|
| [📓 Jupyter Notebook](./Project%20-%20Marketing%20Sales%20Prediction%20Linear%20and%20Regularized%20Regression.ipynb) | Complete analysis, model development, diagnostics, and evaluation |
| [📊 Dataset (CSV)](./market_sales%20-%20LMS.csv) | Dataset used for the sales prediction analysis |

## 📊 Dataset Overview

The dataset contains **2,500 rows and 10 columns**, with `Sales` as the target variable.

| Feature | Description |
|---|---|
| `TV_Ad_Spend` | Television advertising expenditure |
| `Social_Media_Spend` | Social media advertising expenditure |
| `Discount_Offers` | Discount or promotional offer information |
| `Search_Engine_Marketing_Spend` | Search engine marketing expenditure |
| `Product_Category` | Product category |
| `Region` | Geographical region |
| `Customer_Segment` | Customer segment |
| `Website_Traffic` | Website traffic |
| `Conversion_Rate` | Conversion rate |
| `Sales` | Target variable to predict |

## 🛠️ Technologies & Libraries

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Data manipulation:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Statistical analysis:** Statsmodels
- **Machine learning:** Scikit-learn

## ⚙️ Project Workflow

### Part 1: Linear Regression

1. Load and inspect the dataset.
2. Check missing values, duplicates, and data types.
3. Handle missing values and prepare the data.
4. Perform exploratory data analysis and correlation analysis.
5. Encode categorical variables.
6. Fit an Ordinary Least Squares (OLS) statistical model.
7. Train and evaluate a baseline Linear Regression model.
8. Interpret coefficients and compare actual versus predicted sales.
9. Examine regression assumptions using diagnostic checks.

### Part 2: Regularized Regression

1. Scale features for regularized modeling.
2. Train Ridge Regression using L2 regularization.
3. Train Lasso Regression using L1 regularization.
4. Train ElasticNet using a combination of L1 and L2 regularization.
5. Tune hyperparameters using 5-fold cross-validation.
6. Compare models using mean RMSE, RMSE variability, and R².
7. Inspect coefficient shrinkage and feature selection.
8. Select a final model using cross-validation and test-set performance.

## 📈 Evaluation Metrics

| Metric | Interpretation |
|---|---|
| MAE | Average absolute difference between actual and predicted sales |
| MSE | Average squared prediction error |
| RMSE | Square root of MSE, expressed in the target variable's units |
| R² Score | Proportion of target variance explained by the model |

Lower MAE, MSE, and RMSE generally indicate smaller prediction errors, while a higher R² generally indicates a better fit.

## 🧠 Key Concepts Explored

- Simple and multiple Linear Regression
- Ordinary Least Squares (OLS)
- Regression coefficients and statistical significance
- Multicollinearity and residual diagnostics
- Feature encoding and scaling
- L1 and L2 regularization
- Hyperparameter tuning
- K-Fold cross-validation
- Model comparison and selection

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone <YOUR_REPOSITORY_URL>
cd <YOUR_REPOSITORY_NAME>
```

Replace the placeholders with your actual GitHub repository URL and repository name.

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels jupyter
```

### 3. Open the notebook

```bash
jupyter notebook
```

Open the project notebook and run the cells sequentially.

**Note:** Keep the CSV dataset in the same working directory as the notebook. If necessary, update the dataset filename in the notebook's `pd.read_csv()` statement to match the downloaded CSV file.

## 📌 Results & Model Selection

The notebook compares the baseline Linear Regression model with tuned Ridge, Lasso, and ElasticNet models.

The final model is selected using cross-validation RMSE, prediction performance on the held-out test set, stability, and coefficient interpretability.

Refer to the notebook for the computed evaluation metrics and final model-selection results.

## 👩‍💻 Author

**Chandana Yemul**

- **GitHub:** [chandana1312](https://github.com/chandana1312)
- **LinkedIn:** [Chandana Yemul](https://www.linkedin.com/in/chandana-yemul-a10348263/)

---

*This project demonstrates a practical workflow for regression modeling, statistical interpretation, regularization, and model evaluation.*
