# ml-credit-risk-project
This project used ml models to predict loan defaults and assess borrower risk.

It includes:

Data Cleaning & Outlier Handling – improved data quality with an 8% accuracy boost.

EDA & Feature Engineering – applied VIF to remove multicollinear features and WOE/IV for categorical selection.

Class Imbalance Handling – used SMOTETomek to balance default vs. non-default cases.

Model Training & Optimization – compared Random Forest, XGBoost, and Logistic Regression with hyperparameter tuning (RandomizedSearchCV).

Best Model – Logistic Regression achieved 94% recall, ensuring reliable detection of high-risk borrowers.

The repository demonstrates a complete workflow from raw data processing to model evaluation, offering a scalable solution for credit risk assessment in NBFCs and financial institutions.
