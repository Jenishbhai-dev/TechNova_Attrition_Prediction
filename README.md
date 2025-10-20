# TechNova_Attrition_Prediction
TechNova Solutions, a mid-sized IT services company with ~1,200 employees, has been facing an attrition rate. Despite offering competitive salaries and benefits, the company struggles to retain talent, particularly in technical and client-facing roles. This turnover has increased costs, delayed projects, and reduced overall employee satisfaction.

Objectives
Understand employee attrition: Explore which features (e.g., age, role, overtime, satisfaction) are most linked to employee departures.

Build a predictive model: Use historical HR data to predict which employees are most likely to leave.

Provide actionable recommendations: Connect model findings to realistic, data-driven HR strategies.

Project Structure
app.ipynb: Main Jupyter notebook — all analysis, code, visualizations, and recommendations.

employee_churn_dataset.csv: Employee data for model training.

employee_churn_data_dictionary.csv: Explains each column in the dataset.

TechNova_AttritionPrediction_TechSpec_Jenishbhai.pdf: Technical specification document guiding project steps.

Employee-Churn-Task: Brief assignment prompt or rubric (if provided).

README.md: This file, summarizing the logic, steps, and outcomes.

Workflow
Context & Problem Setup: Describes why attrition matters, sets business background.

Data Understanding: Inspects dataset columns, missing values, and target definition.

EDA: Shows trends and patterns (e.g., high churn in some roles/departments, or with low satisfaction).

Preprocessing: Cleans, encodes, and scales features to prepare for modeling.

Feature Engineering: Creates new variables, e.g., tenure bins, to capture more data relationships.

Experiment Design: Details modeling approach, cross-validation, and evaluation metrics.

Modeling & Evaluation: Builds Logistic Regression and Random Forest models. Evaluates with classification metrics, ROC curves, and feature importance.

Explainability: Highlights top features that influence churn predictions.

Recommendations: Connects insights to HR strategies—such as reducing overtime, increasing satisfaction, and supporting new hires.

Key Findings
Top drivers of churn: Overtime hours, low satisfaction, lack of promotions, and short tenure.

Model accuracy: Random Forest model achieved high recall and ROC AUC, best for identifying at-risk employees.

HR impact: Targeted programs (like mentoring, improved promotion processes, and better work-life balance) can reduce attrition.

How to Run
Clone or download the repository.

Open app.ipynb in Jupyter Notebook, JupyterLab, or VS Code.

Run all cells in order for analysis, modeling, and HR recommendations.

Make sure all dataset files are in the same folder.

Dependencies needed: pandas, numpy, matplotlib, seaborn, scikit-learn.

Results and Recommendations
The notebook ends with practical HR strategies, clearly connected to model insights. These are ready for TechNova’s HR team to implement.

Author
Prepared by Jenishbhai
