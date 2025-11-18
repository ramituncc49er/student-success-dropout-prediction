# Predict students' dropout and academic success
Predicts whether a student will drop out, continue, or graduate based on academic, financial, and demographic variables. The project includes preprocessing, feature engineering, correlation analysis, cross-validated evaluation and comparing several classical ML models.

What the project does:
- Perform data preprocessing & feature engineering with pandas / scikit-learn
- Use correlation analysis and mutual information for manual feature selection of the most predictive features
- Train and benchmark multiple models:
    - Logistic Regression (L1), Random Forest, ExtraTrees
    - LightGBM, CatBoost, XGBoost

# Dataset

Kaggle dataset, which contains data from a higher education institution on various variables related to undergraduate students, including demographics, social-economic factors, and academic performance, to investigate the impact of these factors on student dropout and academic success

- Marital status: The marital status of the student. (Categorical)
- Application mode: The method of application used by the student. (Categorical)
- Application order: The order in which the student applied. (Numerical)
- Course: The course taken by the student. (Categorical)
- Daytime/evening attendance: Whether the student attends classes during the day or in the evening. (Categorical)
- Previous qualification: The qualification obtained by the student before enrolling in higher education. (Categorical)
- Nacionality: The nationality of the student. (Categorical)
- Mother's qualification: The qualification of the student's mother. (Categorical)
- Father's qualification: The qualification of the student's father. (Categorical)
- Mother's occupation: The occupation of the student's mother. (Categorical)
- Father's occupation: The occupation of the student's father. (Categorical)
- Displaced: Whether the student is a displaced person. (Categorical)
- Educational special needs: Whether the student has any special educational needs. (Categorical)
- Debtor: Whether the student is a debtor. (Categorical)
- Tuition fees up to date: Whether the student's tuition fees are up to date. (Categorical)
- Gender: The gender of the student. (Categorical)
- Scholarship holder: Whether the student is a scholarship holder. (Categorical)
- Age at enrollment: The age of the student at the time of enrollment. (Numerical)
- International: Whether the student is an international student. (Categorical)
- Curricular units 1st sem (credited): The number of curricular units credited by the student in the first semester. (Numerical)
- Curricular units 1st sem (enrolled): The number of curricular units enrolled by the student in the first semester. (Numerical)
- Curricular units 1st sem (evaluations): The number of curricular units evaluated by the student in the first semester. (Numerical)
- Curricular units 1st sem (approved): The number of curricular units approved by the student in the first semester. (Numerical)

## Repository Structure

```text
legal_rag_assistant/
├─src/
│ ├─ students_success_dropout_3
│
├─ README.md
├─ LICENSE
└─ .gitignore
```
## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.
