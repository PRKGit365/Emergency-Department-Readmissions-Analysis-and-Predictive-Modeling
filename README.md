# Emergency-Department-Readmissions-Analysis-and-Predictive-Modeling

## 📊 EMERGENCY DEPARTMENT READMISSIONS ANALYSIS AND PREDICTIVE MODELING (PYTHON & JUPYTER NOTEBOOKS)
📖 **Description**  

This SkillUp.online project applies statistical analysis and predictive modeling techniques to a realistic healthcare operations scenario using Python and Jupyter Notebook. It includes end-to-end analysis with emergency department (ED) visit data—exploring patterns, testing hypotheses, and building models that support data-driven operational and clinical decision-making.


📈 **Project Scenario**  

Role: Healthcare Data Analyst working with the Emergency Department (ED) operations team at a large urban hospital.  
ED leadership has raised concerns about:  
* Prolonged length of stay (LOS) in the emergency department
* Differences in patient outcomes across triage severity levels
* The ability to identify patients likely to be admitted as early as possible
* To support these goals, you have been asked to analyze historical ED visit data and build both statistical tests and predictive models that can
  inform operational planning and early risk stratification.    

  
🧠 **Objectives**

* Explore and summarize healthcare datasets using descriptive statistics
* Perform hypothesis testing to compare patient groups
* Use ANOVA to analyze differences across multiple triage categories
* Build and evaluate a logistic regression model for admission prediction
* Train and compare tree-based machine learning models
* Interpret analytical results in an operational healthcare context

🎯 **Key Healthcare Analytics Insights**  

Operational Interpretation:  Extended emergency department stays and extensive diagnostic testing strongly correlate with higher hospital admission rates. Harnessing these metrics can empower clinicians to identify high-risk patients earlier, driving timely interventions and supporting operational decision-making.

Statistical Analysis Insights:    

* The independent-samples t-test revealed a statistically significant difference in length of stay between admitted and non-admitted patients, suggesting a
  critical influence of this metric on patient outcomes.
* The logistic regression model demonstrated an admission risk prediction accuracy of 0.69. However, the modest AUC, potentially driven by dataset imbalance,
  underscores the need for more robust predictive strategies to elevate clinical decision support.
* The one-way ANOVA did not show a statistically significant difference in length of stay across low-, medium-, and high-triage groups.
* Model performance could likely be improved by incorporating additional clinically relevant predictors and applying regularization methods, such as LASSO, to
  reduce overfitting and improve generalizability.

🔍 **Dataset Overview**  

Rows: 400  
Columns: 7  
Fields:  
* Visit ID
* Age
* Triage Level
* Arrival Hour
* Emergency Department Length of Stay (LOS)
* Number of Tests Ordered
* Admitted (whether or not patient was admitted)


 🛠 **Tools & Technologies**
 
* Python: Pandas, NumPy, Seaborn, Matplotlib
* Jupyter Notebook
