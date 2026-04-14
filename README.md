

# Heart Disease Risk Stratification Tool

## Project Overview
This project is an end-to-end Machine Learning pipeline designed to predict Heart disease risk based on clinical patient markers. By utilizing historical health data, we built a tool that assists healthcare providers in identifying high-risk individuals for early intervention.


## Key Features
* **Predictive Pipeline:** Compares **Logistic Regression** (baseline) and **Random Forest** (ensemble) models to optimize classification accuracy and clinical safety.
* **Data Handling:** Implemented robust preprocessing, including Random Weighted Imputation for missing values and One-Hot Encoding for categorical data.
* **Clinical Safety:** Prioritized **Recall** over accuracy to minimize False Negatives, ensuring fewer at-risk patients go undetected.
* **Interactive GUI:** Deployed via **Streamlit**, allowing clinicians to input patient data and receive real-time risk stratification.

## Tech Stack
* **Language:** Python 3.x
* **Core Libraries:** `pandas`, `scikit-learn`, `numpy`, `seaborn`, `matplotlib`
* **Deployment:** `streamlit`, `joblib`

## Project Architecture


## Performance Comparison
| Model | Accuracy | Recall (Key Metric) |
| :--- | :--- | :--- |
| **Logistic Regression** | 87% | 82% |
| **Random Forest** | 100% | 100% |

*Note: The Random Forest performance suggests potential overfitting; the Logistic Regression model provides a more realistic clinical baseline.*

## How to Run the Project
1. **Clone the repository:**
   ```bash
   git clone [your-repo-link]

## AUTHORS
ALAKIIR CHOL
BANGMIA GILLIAN 

