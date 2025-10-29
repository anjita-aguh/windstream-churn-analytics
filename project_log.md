## 🗓️ Week 1 – Project Initialization
- Set up virtual environment and installed dependencies  
- Loaded Windstream dataset (243 k rows × 14 columns)  
- Explored data types and checked for nulls  
- Defined initial project goal: Predict customer churn for Windstream users  
- Created GitHub repository and pushed initial structure  

---
## 🗓️ Week 2 – Data Cleaning & Preprocessing
- Converted date_of_registration → datetime  
- Created derived feature `tenure_days`  
- Handled categorical encoding (gender, state, city, telecom_partner)  
- Verified dataset shape and memory usage  
- Prepared for feature scaling

- ## Week 1: Data Understanding & Model Foundation

- imported dataset and checked shape & datatypes  
- removed duplicates and handled nulls  
- performed exploratory data analysis (EDA)  
- identified key numerical and categorical features  
- encoded categorical columns using LabelEncoder  
- split dataset into train/test sets (80/20)  
- applied StandardScaler for feature scaling  
- trained baseline Logistic Regression model  
- evaluated accuracy (~81%) and confusion matrix  
- saved EDA plots and cleaned dataset in reports folder  

---

## Week 2: Model Optimization & Visualization

- trained Random Forest and XGBoost models for comparison  
- tuned hyperparameters for optimal performance  
- achieved improved accuracy (~87%) and F1 score (~0.84)  
- saved best model as rf_churn_model.pkl  
- prepared Power BI and Tableau dashboards (draft visuals)  
- added new KPI: churn by telecom partner and tenure buckets  
- updated project documentation & requirements.txt  
- pushed all changes to GitHub repository  
- prepared roadmap for next sprint (model explainability + deployment)

## Week 3: Model Explainability & Insights

- integrated SHAP and LIME for feature importance visualization  
- analyzed top 10 drivers of customer churn (age, tenure_days, estimated_salary, data_used, etc.)  
- created feature importance plots and correlation heatmaps  
- documented insights in `/reports/model_insights.md`  
- discussed model interpretability results with the analytics lead  
- started exploring uplift modeling for targeted retention strategies  
- presented weekly progress in team sync meeting  

---

## Week 4: Model Deployment & Monitoring Setup

- containerized the final model using Docker  
- created a simple FastAPI app for serving churn predictions  
- wrote API documentation (`/docs/api_reference.md`)  
- deployed model locally and tested endpoints using Postman  
- added model performance tracking and logging mechanisms  
- created monitoring dashboard using Strea

