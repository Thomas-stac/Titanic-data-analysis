# Titanic Data Analysis & Classification

## 📋 Brief Description and Context

This project was undertaken as part of a data science assignment to analyze and classify Titanic passenger survival data. The goal was twofold:
1. Perform exploratory data analysis (EDA) to identify patterns and trends.
2. Build and optimize a **Decision Tree Classifier** to predict survival outcomes based on passenger attributes.

The dataset used for this analysis contains detailed information about the passengers aboard the Titanic, including demographic details, ticket information, and survival status. Through this project, we explored the impact of factors such as **gender**, **age**, and **passenger class** on survival rates.

---

## 🏆 Achievements

- **Data Cleaning and Preprocessing**: Addressed missing values through various imputation techniques (mean, median, and mode), and removed non-essential columns to streamline the dataset.
- **Exploratory Data Analysis (EDA)**: Uncovered key insights, such as the significantly higher survival rate of women compared to men.
- **Feature Engineering**: Applied one-hot encoding to categorical variables (e.g., gender and embarkation port) to prepare the data for classification.
- **Model Training and Optimization**: Built and fine-tuned a **Decision Tree Classifier**, achieving:
  - Training accuracy: 99%
  - Testing accuracy: 82%
- **Visualization**: Created intuitive graphs and charts to communicate insights, including survival distributions and model decision paths.

---

## 🎯 Responsibilities

### Data Cleaning
- Handled missing values in critical columns such as **Age**, **Cabin**, and **Embarked**.
- Justified the removal of high-percentage missing columns like **Cabin**, and replaced null values in **Age** with mean/median values.

### Exploratory Data Analysis (EDA)
- Conducted survival rate analysis by gender, age group, and embarkation port.
- Visualized survival proportions using **Seaborn** bar plots and distribution charts.

### Feature Engineering
- Applied one-hot encoding to categorical features, transforming them into numeric form for model compatibility.
- Selected relevant features based on correlation analysis.

### Model Development and Evaluation
- Split the dataset into training and testing sets (80/20 split).
- Trained and evaluated a **Decision Tree Classifier**, experimenting with hyperparameters such as `max_depth` to mitigate overfitting.
- Performed a depth analysis to identify the optimal tree structure.

---

## 🛠️ Technology Stack

- **Programming Language**: Python  
- **Libraries**:
  - `Pandas`: For data handling and cleaning.
  - `Seaborn`: For data visualization.
  - `Scikit-learn`: For machine learning and decision tree implementation.
  - `Matplotlib`: For plotting decision tree structures.

---

## 🔍 Sample Outputs

### Survival Rate by Gender

| Gender | Total Passengers | Survivors | Survival Rate (%) |
|--------|------------------|-----------|-------------------|
| Male   | 577              | 109       | 18.89            |
| Female | 314              | 233       | 74.20            |

### Decision Tree Metrics
- Training Accuracy: **99%**
- Testing Accuracy: **82%**
- Optimal Tree Depth: **3**

---

## 🖥️ Key Code Snippets

The complete code for this project is available in the **notebook attached to this page**. Please refer to the notebook for a detailed view of the code used for data cleaning, feature engineering, model training, and visualization.

