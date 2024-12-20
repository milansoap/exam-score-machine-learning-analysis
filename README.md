## 📌 **Overview**
This project analyzes student performance based on various factors like attendance, parental involvement, motivation, and access to resources.
Leveraging machine learning and statistical analysis, it provides insights into the predictors of academic success.


## 📝 **Dataset**
The dataset includes 20 features and 1 target variable:
| Feature                  | Description                          |
|--------------------------|--------------------------------------|
| `Hours_Studied`          | Hours spent studying weekly          |
| `Attendance`             | Percentage of class attendance       |
| `Parental_Involvement`   | Level of parental engagement (Low/High) |
| `Access_to_Resources`    | Availability of study resources      |
| `Extracurricular_Activities` | Participation in extracurricular activities |
| `Sleep_Hours`            | Average sleep hours                  |
| `Previous_Scores`        | Scores from previous exams           |
| `Motivation_Level`       | Level of motivation                  |
| `Internet_Access`        | Internet availability (Yes/No)       |
| `Tutoring_Sessions`      | Count of tutoring sessions attended  |
| `Teacher_Quality`        | Perceived quality of teachers        |
| `Peer_Influence`         | Influence of peers                   |
| `Physical_Activity`      | Hours of physical activity           |
| `Gender`                 | Student gender                       |
| **Target**: `Exam_Score` | Final exam score                     |

---

## 🚀 **Tech Stack**
- **Python**: Data processing and modeling
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost
- **ML Techniques**: 
  - Regression (Linear, Ridge, Lasso, Decision Tree)
  - Clustering (K-means, Hierarchical)
  - Classification (Logistic Regression, SVM)
  - Ensemble Models (Random Forest, Gradient Boosting, Homogeneous Ensemble)
---

## 📈 **Key Analysis & Methods**
1. **Exploratory Data Analysis (EDA):**
   - Complex graphs for correlations between study factors and scores.
   - Insights into the relationship between sleep, attendance, and exam performance.

2. **Regression Analysis:**
   - Predicting exam scores using regression models (Linear, Ridge, and Lasso).

3. **Clustering Analysis:**
   - Grouping students based on study habits and scores (K-Means Clustering).

4. **Classification Models:**
   - Classifying students into high, medium, and low performers.

5. **Ensemble Methods:**
   - Homogeneous and heterogeneous ensemble models with combination of Neural Network for improved prediction accuracy.

---

## 📊 **Results**
- Found strong correlations between attendance, sleep hours, and exam scores.
- Ensemble methods outperformed single models in accuracy and robustness.
- Visualizations clearly highlight the factors influencing performance.
