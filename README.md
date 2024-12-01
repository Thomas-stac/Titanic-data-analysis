# Titanic data analysis & classification

## 📋 Brief description and context

This project was undertaken as part of a data science assignment to analyze and classify Titanic passenger survival data. The goal was twofold:
1. Perform exploratory data analysis (EDA) to identify patterns and trends.
2. Build and optimize a **Decision Tree Classifier** to predict survival outcomes based on passenger attributes.

The dataset used for this analysis contains detailed information about the passengers aboard the Titanic, including demographic details, ticket information, and survival status. Through this project, we explored the impact of factors such as **gender**, **age**, and **passenger class** on survival rates.

---

## 🏆 Achievements

- **Data cleaning and preprocessing**: Addressed missing values through various imputation techniques (mean, median, and mode), and removed non-essential columns to streamline the dataset.
- **Exploratory data analysis (EDA)**: Uncovered key insights, such as the significantly higher survival rate of women compared to men.
- **Feature engineering**: Applied one-hot encoding to categorical variables (e.g., gender and embarkation port) to prepare the data for classification.
- **Model training and optimization**: Built and fine-tuned a **Decision Tree Classifier**, achieving:
  - Training accuracy: 99%
  - Testing accuracy: 82%
- **Visualization**: Created intuitive graphs and charts to communicate insights, including survival distributions and model decision paths.

---

## 🎯 Responsibilities

### Data cleaning
- Handled missing values in critical columns such as **Age**, **Cabin**, and **Embarked**.
- Justified the removal of high-percentage missing columns like **Cabin**, and replaced null values in **Age** with mean/median values.

### Exploratory data analysis (EDA)
- Conducted survival rate analysis by gender, age group, and embarkation port.
- Visualized survival proportions using **Seaborn** bar plots and distribution charts.

### Feature engineering
- Applied one-hot encoding to categorical features, transforming them into numeric form for model compatibility.
- Selected relevant features based on correlation analysis.

### Model development and evaluation
- Split the dataset into training and testing sets (80/20 split).
- Trained and evaluated a **Decision Tree Classifier**, experimenting with hyperparameters such as `max_depth` to mitigate overfitting.
- Performed a depth analysis to identify the optimal tree structure.

---

## 🛠️ Technology stack

- **Programming language**: Python  
- **Libraries**:
  - `Pandas`: For data handling and cleaning.
  - `Seaborn`: For data visualization.
  - `Scikit-learn`: For machine learning and decision tree implementation.
  - `Matplotlib`: For plotting decision tree structures.

---

## 🔍 Sample outputs

### Survival rate by gender

| Gender | Total Passengers | Survivors | Survival Rate (%) |
|--------|------------------|-----------|-------------------|
| Male   | 577              | 109       | 18.89            |
| Female | 314              | 233       | 74.20            |

### Decision tree metrics
- Training accuracy: **99%**
- Testing accuracy: **82%**
- Optimal tree depth: **3**

---

## 🖥️ Key code snippets

The complete code for this project is available in the notebook attached to this page. Please refer to the notebook for a detailed view of the code used for data cleaning, feature engineering, model training, and visualization.

---

## ✨ Relevance to the i-CITY AI platform development

This project demonstrates a range of skills and techniques directly relevant to the development of the **i-CITY AI Platform** modules:

1. **Data handling and automation**:
   - **Titanic project**: Extensive preprocessing of missing values, categorical data encoding, and dataset transformation using automation pipelines.
   - **i-CITY**: Skills applied to automate analytics for system usage and quality assessments, ensuring robust and efficient data flows.

2. **Visualization and insights communication**:
   - **Titanic project**: Created clear visualizations for survival trends and decision paths, aiding stakeholder understanding.
   - **i-CITY**: Valuable for presenting analytics insights, enhancing system quality monitoring, and designing user-friendly dashboards.

3. **Interface with APIs and modular design**:
   - **Titanic project**: Modular code design for data cleaning, analysis, and model evaluation.
   - **i-CITY**: Skills transferable to API connectivity, ensuring seamless integration of platform modules.

4. **Routing and task assignment**:
   - **Titanic project**: Data-driven decision-making through automated survival classification.
   - **i-CITY**: Foundational knowledge to create routing systems for automated agent task assignments.

By combining expertise in data preprocessing, machine learning, and insights visualization, this project underscores my ability to contribute effectively to Staizen’s **i-CITY AI platform** development.

---

Feel free to explore the attached notebook for detailed implementation.
