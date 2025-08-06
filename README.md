# task-2
# Titanic Dataset - Exploratory Data Analysis (EDA)

This task focuses on understanding the Titanic dataset after it has been cleaned and preprocessed.

---

## 📌 Objective
Analyze the cleaned Titanic dataset to:
1. Summarize numeric features
2. Visualize data distributions
3. Study feature relationships
4. Identify patterns, trends, and anomalies
5. Make basic feature-level inferences

---

## 🛠️ Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📊 Steps Performed

### 1. Summary Statistics
- Used `describe()` to get **mean, median, std, min, max, and quartiles** for numeric features.

### 2. Data Visualizations
- **Histograms** → To view distribution of numeric features.
- **Boxplots** → To detect spread and outliers in numeric features.

### 3. Feature Relationships
- **Pairplot** → To see pairwise relationships between numeric features.
- **Correlation Matrix Heatmap** → To find how strongly features are related.

### 4. Pattern & Trend Checks
- Compared **survival rates by gender** using `groupby('Sex')`.
- Compared **survival rates by passenger class** using `groupby('Pclass')`.

### 5. Key Observations
- Females had higher survival rates than males.
- Passengers in **1st class** had higher survival chances.
- A few passengers had extremely high fares (possible wealth indicators).
- Younger passengers had slightly higher survival chances.

---

## 📁 Output
- Visual plots showing distributions, correlations, and survival trends.
- Feature-level insights for guiding ML model building.

---

## 🚀 Next Step
Use the insights from EDA for feature selection and ML model training.
