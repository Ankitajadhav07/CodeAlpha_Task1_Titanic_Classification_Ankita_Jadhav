# CodeAlpha_Task1_Titanic_Classification_Ankita_Jadhav
# Titanic Classification System Summary

The Titanic Classification system is designed to predict whether a passenger would survive the Titanic disaster based on various factors like socio-economic status, age, gender, and more.


1. **Data Preprocessing**:
   - **Handling Missing Values**: Filled missing values for age and embarked location, and dropped the cabin column due to excessive missing data.
   - **Encoding Categorical Variables**: Converted gender (Sex) to numerical values and applied one-hot encoding for the Embarked feature.

2. **Feature Selection**:
   - Key features used include `Age`, `Fare`, `Pclass` (socio-economic status), `Sex` (gender), `SibSp` (siblings/spouses aboard), `Parch` (parents/children aboard), and `Embarked`.

3. **Data Visualization**:
   - Created visualizations such as histograms, count plots, pie charts, radar charts, bubble charts, and pair plots to explore relationships between features and survival outcomes.

4. **Model Training**:
   - A **Random Forest Classifier** was used to build the prediction model.
   - **Hyperparameter Tuning**: Grid Search was employed to optimize the model’s performance.

5. **Model Evaluation**:
   - Evaluated the model using accuracy, confusion matrix, and feature importance to understand the model’s predictive power and key factors influencing survival.

6. **Prediction**:
   - The system can predict whether a new passenger would survive, providing insights into the factors most likely to contribute to survival, such as socio-economic status, age, and gender.

### Key Factors Influencing Survival:
- **Gender**: Females had a higher survival rate.
- **Passenger Class**: Higher-class passengers (1st class) were more likely to survive.
- **Age**: Younger passengers had a slightly better chance of survival.

This system provides a data-driven approach to understanding survival on the Titanic, offering insights that can be applied to similar predictive modeling tasks.
