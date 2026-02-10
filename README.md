**📊 Income Prediction Using Machine Learning**

**🎓 Internship Project – Edunet Foundation (IBM SkillsBuild Collaboration)**
- This project was developed as part of a 6-week internship program conducted by Edunet Foundation in collaboration with IBM SkillsBuild.

- The objective was to apply machine learning techniques to real-world census data and build a classification model to predict whether an individual's income exceeds $50K per year.

- The complete implementation is provided in:
- Income_Prediction_Using_ML.ipynb

Developed using Google Colab.
🏢 Internship Details

- Duration: 6 Weeks

- Organization: Edunet Foundation

- Industry Partner: IBM SkillsBuild

- Role: AI & ML Intern

-Project Type: Supervised Classification (Income Prediction)

**🧠 Project Objective**

To develop a classification model that predicts income category (>50K or <=50K) using real-world census data and to analyze how different features influence income levels.

**📂 Dataset**

Dataset contains 48,842 records

15 original features including:

- Age

- Workclass

- Education

- Marital Status

- Occupation

- Relationship

- Race

- Gender

- Capital Gain / Loss

- Hours per Week

- Native Country

- Income (Target)

- Target Variable:

- income_>50K (Binary Classification)

**🛠 Technologies Used**

- Python

- Google Colab

- Pandas

- NumPy

- Matplotlib

- Scikit-learn

**🔍 Data Preprocessing Steps **
✔ Dropped irrelevant columns (fnlwgt, education)
✔ Handled missing values represented as "?"
✔ Removed invalid categories (Without-pay, Never-worked)
✔ Outlier removal using boxplot analysis (Age filtering)
✔ One-Hot Encoding using pd.get_dummies()
✔ Feature Scaling using StandardScaler
✔ Train-Test Split (80-20 split)

Final dataset shape after preprocessing:
48,438 rows × 83 features

🤖 Models Implemented
1️⃣ Logistic Regression

- Max iterations: 1000

- Standardized features

- Accuracy: 85.08%

- Classification Performance:

- Strong precision for <=50K

- Moderate recall for >50K

2️⃣ Random Forest Classifier

- class_weight='balanced'

- Random State: 42

- Accuracy: 84.23%

Also used for:

- Feature importance analysis

- Demographic trend visualization

**📈 Model Comparison**
- Model	Accuracy
- Logistic Regression	85.08%
- Random Forest	84.23%

* Logistic Regression performed slightly better overall.

**📊 Data Analysis & Visualization**

The project includes advanced analysis such as:

✔ Income prediction vs Age trends
✔ Education level vs Income probability
✔ Marital Status impact analysis
✔ Workclass comparison
✔ Top 10 important features (Random Forest)

Feature importance analysis helps understand which factors most influence income classification.

🚀 How to Run

Clone the repository:

"git clone https://github.com/ponnada-sowjanya/income-prediction.git"


Open in:

- Google Colab (Recommended)
or

- Jupyter Notebook

- Run all cells sequentially.

**🎯 Key Learning Outcomes**

- Through this project, I gained practical experience in:

- Data cleaning & preprocessing

- Handling categorical variables

- Feature scaling

- Classification algorithms

- Model comparison

- Performance evaluation

- Feature importance interpretation

- Real-world ML workflow

📫 Contact

📧 ponnadasowjanya4@gmail.com
