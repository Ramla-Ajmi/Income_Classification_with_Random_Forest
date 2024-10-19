Project Overview :

This project demonstrates how to build and tune a Random Forest Classifier for income classification. The model predicts whether a person's income is greater than or less than $50K based on various features such as age, education, race, and hours worked per week.


Dataset :

The dataset consists of demographic information and includes the following features :
- age : Age of the individual.
- workclass : Type of employment (e.g., Private, Self-employed).
- education : Education level (e.g., Bachelors, HS-grad).
- occupation : Type of occupation (e.g., Tech-support, Craft-repair).
- hours-per-week : Number of hours worked per week.
- race : Race of the individual.
- income : Binary target variable (`<=50K` or `>50K`).


Key Features of the Project : 

- Data Preprocessing :
  - Cleaned categorical columns by stripping extra spaces.
  - Generated dummy variables for categorical features.
  - Created additional features using education levels.

- Model Building :
  - Random Forest Classifier used to predict income.
  - Hyperparameter tuning for `max_depth` to improve model performance.

- Model Evaluation :
  - Plotted accuracy scores for different depths to visualize overfitting/underfitting.
  - Identified the most important features influencing the predictions.


Dependencies :

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn`
"# Income_Classification_with_Random_Forest" 
