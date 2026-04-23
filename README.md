Churn Prediction Model
Goal: Predict which users are likely to cancel their subscription so the retention team can intervene proactively.

Pipeline:

Synthetic data generation
Exploratory Data Analysis (EDA)
Feature Engineering
Model Training & Comparison (Logistic Regression, Random Forest, XGBoost)
Evaluation & Threshold Tuning
Feature Importance & Business Insights


| Section | Contents |
|---|---|
| **Overview** | Goal, what the pipeline does, target metrics achieved |
| **Problem Statement** | Binary classification framing |
| **Dataset** | All 20+ features tabulated by group, churn label formula |
| **Project Structure** | File tree |
| **Pipeline** | Full ASCII flowchart from raw data to risk tiers |
| **Feature Engineering** | Every derived feature with its formula and business rationale |
| **Models** | Hyperparameters, training strategy (SMOTE vs class_weight), XGBoost fallback note |
| **Results** | Model comparison table, risk tier distribution |
| **Installation** | Python deps, Homebrew note for macOS/XGBoost |
| **Usage** | Jupyter, Kaggle, script, section-by-section guide |
| **Business Insights** | Driver → observation → retention action table |
| **Future Work** | SHAP, Optuna, real data, FastAPI deployment |
