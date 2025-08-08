# 🚀 Applied Data Science Capstone

This capstone project is the final (10th) course in the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) specialization.  
It serves as a culmination of all skills and concepts learned throughout the program, applied to a real-world data science problem.

---

## 📄 Project Background

SpaceX has transformed commercial spaceflight by drastically reducing launch costs through reusability—particularly, the reuse of the **first stage of the Falcon 9 rocket**.

While SpaceX offers launches at **$62 million**, other providers charge over **$165 million**. The ability to **successfully land and reuse** the rocket's first stage is a major cost-saving factor.

This project aims to **predict whether the first stage of a Falcon 9 launch will land successfully**, using public data and machine learning. Accurate predictions can help estimate launch costs and support strategic decision-making.

---

## ❓ Key Questions

- How do variables such as **payload mass**, **launch site**, **number of flights**, and **orbit type** impact landing success?
- Has the **success rate** of landings improved over time?
- Which **classification algorithm** performs best for this task?

---

## 🧪 Methodology

### 1. Data Collection

- Data gathered using the **SpaceX REST API**
- Additional launch data scraped from **Wikipedia**

### 2. Data Wrangling

- Filtered and cleaned raw data
- Handled missing values appropriately
- Used **One-Hot Encoding** to convert categorical features for ML models

### 3. Exploratory Data Analysis (EDA)

- Explored data using **SQL queries** and **visualizations**
- Analyzed feature relationships and correlations with landing outcomes

### 4. Interactive Visual Analytics

- Mapped launch sites and outcomes using **Folium**
- Created an interactive dashboard with **Plotly Dash** for deeper insights

### 5. Predictive Modeling

- Developed multiple **classification models**:
  - Logistic Regression
  - Support Vector Machine
  - Decision Tree
  - K-Nearest Neighbors

- Performed **hyperparameter tuning** using GridSearchCV
- Evaluated model performance using:
  - Accuracy
  - Precision
  - Recall
  - Confusion Matrix

- **Decision Tree Classifier** achieved the best performance overall

---

## 📁 Project Structure (optional)


