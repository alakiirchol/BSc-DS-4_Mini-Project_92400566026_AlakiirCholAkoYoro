#  Heart Disease Prediction using Machine Learning

##  Project Overview

This project aims to predict the likelihood of heart disease using machine learning techniques. It involves data 
preprocessing, exploratory data analysis, model training, and evaluation using two different algorithms.

---

##  Objective

To build and compare machine learning models that can accurately predict whether a patient is likely to have heart 
disease based on medical and lifestyle factors.

---

##  Dataset

* The dataset contains **1000 records** with **16 features**
* Includes attributes such as:

  * Age
  * Cholesterol
  * Blood Pressure
  * Smoking habits
  * Exercise levels
  * Diabetes, Obesity, etc.

---

##  Data Preprocessing

* Removed **duplicate records**
* Dropped **"Alcohol Intake"** column due to ~34% missing values
* Encoded categorical variables using **one-hot encoding**
* Cleaned column names to remove formatting issues

---

##  Exploratory Data Analysis (EDA)

* Correlation matrix used to identify relationships between variables
* Key findings:

  * **Age** showed the strongest correlation with heart disease
  * **Cholesterol** had moderate correlation
  * Most lifestyle features showed weak linear correlation
 
  

---

##  Models Used

### 1. Random Forest Classifier

* Handles non-linear relationships
* Robust to feature interactions

### 2. Logistic Regression

* Used as a baseline model
* Works well for linear relationships

---

##  Model Training

* Data split into:

  * **80% training**
  * **20% testing**
* Logistic Regression used **feature scaling**
* Random Forest used raw data

---

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Random Forest       | 100%     |
| Logistic Regression | 87%      |

---

##  Confusion Matrix Analysis

### Random Forest

* Perfect classification (no errors)
* Indicates possible **overfitting or highly separable data**

### Logistic Regression

* Some false positives and false negatives
* More **realistic and generalizable performance**

---

##  Key Insights

* Age is the most significant predictor of heart disease
* Random Forest captures complex patterns better than Logistic Regression
* Perfect accuracy should be interpreted with caution

---

##  Limitations

* High missing data in "Alcohol Intake" led to feature removal
* Potential overfitting in Random Forest model
* Dataset may be simplified or synthetic

---

##  Future Improvements

* Apply cross-validation for better model evaluation
* Try additional models (e.g., SVM, XGBoost)
* Perform feature engineering
* Use real-world datasets for better generalization

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn

---

##  Conclusion

This project demonstrates how machine learning can be applied to predict heart disease. 
While Random Forest achieved perfect accuracy, Logistic Regression provided a more realistic baseline. 
The comparison highlights the importance of evaluating model performance critically.

---

##  How to Run

1. Clone the repository
2. Install required libraries:

   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter Notebook

---

##  Author

* Alakiir Chol Akoi
* Bangmia Gillian Jabosung

---

