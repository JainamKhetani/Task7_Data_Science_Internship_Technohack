# 🤖 Task 7: Machine Learning Model Development  
# Flipkart Product Intelligence & Customer Analytics System

### TechnoHacks Data Science Internship

---

# 📌 1. Project Overview

This project focuses on developing a Machine Learning model using the Flipkart E-Commerce Dataset to predict discounted product prices based on product attributes and engineered features.

After completing:
- Data Collection
- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Feature Engineering
- Statistical Analysis

the dataset was transformed into a machine learning-ready format.

The primary goal of this task was to train and evaluate a predictive model capable of understanding:
- pricing behavior
- discount patterns
- brand influence
- product popularity
- customer-oriented pricing trends

The project demonstrates a complete machine learning workflow from:
- data preparation
to
- model training
and
- predictive analysis.

---

# 🎯 2. Objective

The main objectives of this task are:

✅ To prepare machine learning input features  
✅ To split the dataset into training and testing data  
✅ To train a regression-based machine learning model  
✅ To predict discounted product prices  
✅ To evaluate model performance  
✅ To analyze feature importance  
✅ To generate prediction visualizations  
✅ To save the trained machine learning model  

---

# 📂 3. Dataset Information

### 📌 Dataset Name
**Flipkart E-Commerce Product Dataset**

### 📌 Dataset Source
Kaggle

### 📌 Dataset Link
https://www.kaggle.com/datasets/PromptCloudHQ/flipkart-products

### 📌 Dataset Size
- Approximately 20,000 rows
- Multiple product-related attributes

---

# 🛠️ 4. Technologies and Libraries Used

## 💻 Programming Language
- Python

## 🧑‍💻 Development Environment
- Visual Studio Code
- Jupyter Notebook

## 📚 Libraries Used

| Library | Purpose |
|---|---|
| Pandas | Data handling and preprocessing |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Visualization and analysis |
| Scikit-learn | Machine learning model development |
| Pickle | Model saving |
| Logging | Workflow logging |

---

# 🗂️ 5. Project Folder Structure

```plaintext
Task_07_Machine_Learning_Model/
│
├── notebooks/
│   └── task7_machine_learning_model.ipynb
│
├── data/
│   ├── X_train.csv
│   ├── X_test.csv
│   ├── y_train.csv
│   └── y_test.csv
│
├── models/
│   └── random_forest_model.pkl
│
├── outputs/
│   ├── reports/
│   │   └── model_summary.csv
│   │
│   └── visualizations/
│       ├── feature_importance.png
│       └── actual_vs_predicted.png
│
├── logs/
│   └── machine_learning.log
│
├── README.md
│
└── requirements.txt
```

---

# ⚙️ 6. Machine Learning Workflow

The following machine learning steps were performed:

### 🔹 Step 1: Dataset Loading
Loaded the feature engineered dataset generated in Task 5.

---

### 🔹 Step 2: Dataset Inspection
Checked:
- dataset structure
- dimensions
- feature availability
- target variable

---

### 🔹 Step 3: Feature Selection
Selected important engineered features for model training.

### 📌 Features Used
- retail_price
- discount_percentage
- product_name_length
- description_length
- brand_frequency
- product_rating

### 📌 Target Variable
- discounted_price

---

### 🔹 Step 4: Train-Test Splitting
Split the dataset into:
- training data
- testing data

using:
```python
train_test_split()
```

This ensures proper model evaluation on unseen data.

---

### 🔹 Step 5: Model Development
Developed a:
## 🌲 Random Forest Regressor

The model learned pricing relationships and discount behavior from the dataset.

---

### 🔹 Step 6: Prediction Generation
Generated discounted price predictions on test data.

The model attempted to estimate:
```plaintext
discounted_price
```
based on engineered product features.

---

### 🔹 Step 7: Model Evaluation
Evaluated model performance using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R2 Score

These metrics helped measure:
- prediction accuracy
- error rate
- model reliability

---

### 🔹 Step 8: Feature Importance Analysis
Analyzed which features contributed most to predictions.

This helped identify:
- strongest pricing factors
- business-influencing variables
- discount-driving features

---

### 🔹 Step 9: Visualization Generation
Created visualizations for:
- feature importance
- actual vs predicted values

These plots improved model interpretability.

---

### 🔹 Step 10: Model Saving
Saved the trained machine learning model using:
```python
pickle
```

This allows future:
- deployment
- reuse
- prediction systems
- dashboard integration

---

# 📊 7. Machine Learning Model Used

## 🌲 Random Forest Regressor

### Why This Model?
Random Forest Regressor was selected because:
- it handles nonlinear relationships well
- performs strongly on structured datasets
- reduces overfitting
- provides feature importance analysis
- generates stable predictions

---

# 📈 8. Evaluation Metrics Used

| Metric | Purpose |
|---|---|
| MAE | Measures average prediction error |
| MSE | Measures squared prediction error |
| R2 Score | Measures prediction capability |

---

# 📊 9. Visualizations Generated

The following visualizations were created:

## 📌 Feature Importance Plot
Shows which features contribute most to prediction performance.

---

## 📌 Actual vs Predicted Plot
Compares real discounted prices with predicted prices.

This visualization helps understand:
- model accuracy
- prediction alignment
- pricing prediction quality

---

# 📋 10. Feature Importance Insights

The model identified the following features as highly influential:

✅ Retail Price  
✅ Discount Percentage  
✅ Product Rating  
✅ Brand Frequency  

These features strongly affect discounted product pricing in e-commerce platforms.

---

# 💾 11. Outputs Generated

| Output Type | Description |
|---|---|
| Trained Model | Saved Random Forest model |
| Train/Test CSV Files | Split datasets |
| Reports | Model evaluation summary |
| Visualizations | Prediction and feature analysis plots |
| Notebook | Complete ML workflow |

---

# 📁 12. Files Generated

## 📊 Reports
- model_summary.csv

## 📈 Visualizations
- feature_importance.png
- actual_vs_predicted.png

## 🤖 Saved Model
- random_forest_model.pkl

## 🪵 Logs
- machine_learning.log

---

# 🔍 13. Key Insights

## 🔹 Pricing Relationships
Retail price strongly influences discounted product prices.

---

## 🔹 Discount Behavior
Higher discount percentages significantly affect final pricing.

---

## 🔹 Product Influence
Ratings and brand popularity also contribute to pricing trends.

---

## 🔹 Prediction Quality
The machine learning model achieved strong prediction performance with low prediction error.

---

# 🚀 14. Future Improvements

This project can be enhanced further using:

✅ Hyperparameter tuning  
✅ Cross-validation  
✅ XGBoost and LightGBM models  
✅ Deep Learning models  
✅ Recommendation systems  
✅ Real-time deployment using Streamlit  
✅ Flask/FastAPI deployment  
✅ Cloud deployment  

---

# 🏁 15. Conclusion

This project successfully developed a machine learning model capable of predicting discounted product prices using engineered features from the Flipkart E-Commerce Dataset.

The workflow included:
- feature preparation
- train-test splitting
- model training
- prediction generation
- model evaluation
- feature importance analysis

The Random Forest model demonstrated strong predictive capability and generated meaningful business insights related to pricing and discount behavior.

The project forms a strong foundation for future:
- predictive analytics
- recommendation systems
- pricing intelligence
- e-commerce business analytics

---

# 👩‍💻 16. Author

### Khushi Kapatel  
TechnoHacks Data Science Internship

---