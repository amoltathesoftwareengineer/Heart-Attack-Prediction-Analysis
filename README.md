# ❤️ Heart Attack Prediction Analysis

Exploratory data analysis and machine learning models to predict **heart attack risk** from patient health data such as age, blood pressure, cholesterol, heart rate and chest pain type.

> ⚠️ Status: edit the sections below to match your actual dataset, notebooks and results.

> **Disclaimer:** This project is for educational and research purposes only. It is not a medical device and must not be used for diagnosis or treatment decisions.

## 📌 Project Overview

Heart disease is one of the leading causes of death worldwide. Early identification of high-risk patients can help in timely prevention and treatment.

This project analyzes a heart-health dataset to understand which factors are most associated with heart attack risk, and trains classification models to predict whether a patient is at high or low risk.

## 🎯 Objectives

- Clean and preprocess the patient dataset
- Explore patterns and correlations using visualizations
- Identify the key risk factors for heart attack
- Train and compare multiple machine learning models
- Evaluate models using appropriate metrics
- Present clear insights from the analysis

## 📊 Dataset

| Feature | Description |
|---|---|
| `age` | Age of the patient |
| `sex` | Gender of the patient |
| `cp` | Chest pain type |
| `trestbps` | Resting blood pressure |
| `chol` | Serum cholesterol (mg/dl) |
| `fbs` | Fasting blood sugar > 120 mg/dl |
| `restecg` | Resting ECG results |
| `thalach` | Maximum heart rate achieved |
| `exang` | Exercise-induced angina |
| `oldpeak` | ST depression induced by exercise |
| `target` | Heart attack risk (1 = high, 0 = low) |

Source: *add your dataset source here (for example Kaggle or UCI Heart Disease dataset).*

## 🔬 Methodology

1. **Data cleaning:** handle missing values, duplicates and outliers
2. **Exploratory data analysis:** distributions, correlation heatmap, risk by age/sex/cholesterol
3. **Feature engineering:** encoding categorical variables, scaling numeric features
4. **Model training:** train-test split with cross-validation
5. **Evaluation:** accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix
6. **Interpretation:** feature importance and key insights

## 🤖 Models

- Logistic Regression
- K-Nearest Neighbors
- Decision Tree
- Random Forest
- Support Vector Machine
- XGBoost

## 📈 Results

| Model | Accuracy | Precision | Recall | F1-score |
|---|---|---|---|---|
| Logistic Regression | – | – | – | – |
| Random Forest | – | – | – | – |
| ... | – | – | – | – |

*Fill in your actual results.* In medical screening, **recall** is especially important, because missing a high-risk patient is costlier than a false alarm.

## 🔑 Key Insights

- *Add your findings here, for example which features show the strongest relationship with risk.*

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 Getting Started

```bash
git clone https://github.com/amoltathesoftwareengineer/Heart-Attack-Prediction-Analysis.git
cd Heart-Attack-Prediction-Analysis
pip install -r requirements.txt
jupyter notebook
```

Open the notebook and run the cells in order.

## 📁 Project Structure

```
Heart-Attack-Prediction-Analysis/
├── data/              # dataset
├── notebooks/         # analysis and modeling notebooks
├── images/            # charts and plots
├── requirements.txt
└── README.md
```

## 🔮 Future Improvements

- Hyperparameter tuning
- Handling class imbalance (SMOTE)
- Model explainability with SHAP
- Simple web app for risk prediction
- Validation on larger, more diverse datasets

## 🤝 Contributing

Contributions are welcome. Fork the repo, create a branch, commit your changes and open a pull request.

## 📄 License

MIT License. See [LICENSE](https://github.com/amoltathesoftwareengineer/Heart-Attack-Prediction-Analysis/blob/main/LICENSE).

## 👤 Author

Amol Tathe · [LinkedIn](https://linkedin.com/in/amoltathesoftwareengineer) · [GitHub](https://github.com/amoltathesoftwareengineer)
