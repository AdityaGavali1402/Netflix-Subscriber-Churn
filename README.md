# Netflix Subscriber Churn: End-to-End Data Pipeline

## 📌 Project Overview

This project focuses on analyzing Netflix subscriber churn and developing an end-to-end data pipeline using data analytics, SQL, machine learning, deep learning, Excel, and Power BI.

The project uses a single Netflix subscriber churn dataset and gradually transforms raw, uncleaned data into meaningful business insights and predictive models.

## 🎯 Project Objectives

- Clean and preprocess the raw dataset.
- Perform Exploratory Data Analysis (EDA) to identify patterns and trends.
- Use SQL to answer business-related questions.
- Apply feature engineering techniques.
- Build machine learning and deep learning models to predict customer churn.
- Perform additional analysis using Excel.
- Develop an interactive Power BI dashboard.

## 🗂️ Project Roadmap

| Part | Project Stage | Status |
|---|---|---|
| Part 1 | Exploratory Data Analysis (EDA) | ✅ Completed |
| Part 2 | SQL Analysis | 🔄 Upcoming |
| Part 3 | Feature Engineering | 🔄 Upcoming |
| Part 4 | Machine Learning | 🔄 Upcoming |
| Part 5 | Deep Learning | 🔄 Upcoming |
| Part 6 | Excel Analysis | 🔄 Upcoming |
| Part 7 | Power BI Dashboard | 🔄 Upcoming |

## 📊 Part 1: Exploratory Data Analysis (EDA)

### Problem Statement

Customer churn is an important challenge for subscription-based streaming platforms. Understanding customer engagement, satisfaction, subscription plans, and viewing behavior can help identify patterns associated with customers leaving the service.

### Dataset Information

- **Dataset:** `Netflix_Churn_Prediction.csv`
- **Original records:** 1,200
- **Columns:** 9
- **Duplicate records removed:** 24
- **Records after duplicate removal:** 1,176

### Dataset Columns

- `Customer_ID`
- `Age`
- `Tenure_Months`
- `Watch_Hours`
- `Login_Frequency`
- `Plan`
- `Device`
- `Satisfaction_Score`
- `Churn`

### Data Cleaning and Preprocessing

The raw dataset contained inconsistent text formats, missing values, duplicate records, and invalid numerical values.

The following steps were performed:

- Checked and removed duplicate records.
- Handled missing values in numerical and categorical columns.
- Extracted numerical values from inconsistent text formats.
- Identified invalid values and handled outliers.
- Standardized subscription plan and device categories.
- Normalized churn labels into consistent categories.
- Prepared the cleaned dataset for analysis.

### Exploratory Data Analysis

The analysis included:

- Univariate analysis of numerical variables.
- Univariate analysis of categorical variables.
- Churn distribution analysis.
- Satisfaction score versus churn analysis.
- Subscription plan versus churn analysis.
- Watch hours and login frequency analysis.
- Correlation heatmap of numerical variables.

### Key Findings

- **Overall churn rate:** Approximately 15.2% among 1,152 subscribers with known churn status.
- **Customer retention:** 977 subscribers stayed, while 175 subscribers churned.
- **Customer satisfaction:** Churned customers had lower average satisfaction scores than retained customers.
- **Customer engagement:** Churned customers showed lower average watch hours and login frequency.
- **Subscription plans:** Churn percentages varied across subscription plans.
- **Data quality:** Data cleaning was essential because the original columns contained inconsistent formats and invalid values.

### Business Insights

- Lower satisfaction may indicate an increased risk of customer churn.
- Lower viewing activity and login frequency can help identify potentially disengaged subscribers.
- Comparing churn rates across subscription plans may help identify areas for further investigation.
- These findings can support future customer retention analysis and predictive modeling.

## 🛠️ Technology Stack

- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Development Environment:** Jupyter Notebook
- **Upcoming Technologies:** SQL, Machine Learning, Deep Learning, Microsoft Excel, Power BI

## 📁 Project Structure

```text
netflix-subscriber-churn/
│
├── README.md
│
├── Part-1-EDA/
│   ├── README.md
│   ├── Netflix_Churn_EDA.ipynb
│   ├── Netflix_Churn_Prediction.csv
│   ├── Netflix_Cleaned_Dataset.csv
│   └── Netflix_Churn_EDA.pdf
│
├── Part-2-SQL/
├── Part-3-Feature-Engineering/
├── Part-4-Machine-Learning/
├── Part-5-Deep-Learning/
├── Part-6-Excel/
└── Part-7-Power-BI/
```

*Keep only the files that you actually upload, and ensure the filenames match your notebook and dataset.*

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Navigate to the `Part-1-EDA` folder.
5. Open `Netflix_Churn_EDA.ipynb` and run the notebook cells.

## 🔮 Future Enhancements

- Perform business analysis using SQL queries.
- Engineer meaningful features for churn prediction.
- Build and evaluate machine learning classification models.
- Explore deep learning approaches for churn prediction.
- Create an Excel-based analytical report.
- Develop an interactive Power BI dashboard.
- Combine all stages into a complete end-to-end analytical workflow.

## 👨‍💻 Author

**Aditya Gavali**

- GitHub: [AdityaGavali1402](https://github.com/AdityaGavali1402)
- LinkedIn: [Aditya Gavali](https://www.linkedin.com/in/aditya-gavali-5b245b343/)
---

⭐ If you find this project useful, feel free to explore the repository as the remaining stages are added.
