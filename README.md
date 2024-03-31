# bank-marketing-predictive-analysis

This project focused on analyzing a Portuguese bank's marketing campaign data to identify customers more likely to subscribe to term deposits. 
The objective was to enhance the bank's marketing strategies by predicting customer behavior, thereby improving profitability and customer engagement.

**Key Phases of the Project**:
```
    1. Data Exploration and Preprocessing:
      - Loaded the bank-additional-full.csv dataset and performed initial exploration to understand its structure, features, and target variable.
      - Conducted data preprocessing, including handling missing values encoded as 'unknown', applying one-hot encoding to categorical variables, and scaling numerical features.

    2. Exploratory Data Analysis (EDA):
      - Performed EDA to uncover insights from the data, focusing on the distribution of the target variable and the relationship between features and term deposit subscriptions.

    3. Model Preparation and Training:
      - Prepared the data for modeling by splitting it into training and testing sets, ensuring stratification to maintain class proportions due to observed imbalance in the target variable.
      - Trained a baseline Logistic Regression model, evaluating its performance in terms of accuracy, precision, recall, F1-score, and ROC-AUC.

    4. Addressing Class Imbalance:
      - Adjusted the Logistic Regression model to account for class imbalance by modifying class weights, which improved recall for the minority class but reduced precision due to an increase in false positives.

    5. Random Forest Model:
      - Implemented a Random Forest Classifier, noted for its robustness and ability to handle imbalanced data, to potentially improve model performance.
      - Evaluated the Random Forest model, which showed a better balance between precision and recall for the minority class and higher overall accuracy compared to the Logistic Regression model.
```
**Conclusions**:
- The analysis demonstrated the complexity of predicting term deposit subscriptions, influenced by factors like class imbalance and the choice of model and evaluation metrics.
- The Random Forest model emerged as a promising approach, offering a better balance between identifying potential subscribers (recall) and minimizing false positives (precision).

**Recommendations for Next Steps**:
- Further explore feature engineering and selection based on model insights.
- Experiment with additional models and advanced techniques like Gradient Boosting or XGBoost.
- Fine-tune models through hyperparameter optimization and explore strategies to address class imbalance more effectively.
- Consider the practical deployment of the model, integrating predictive insights into the bank's marketing strategies to target potential subscribers more effectively.
This project highlights the potential of machine learning to enhance decision-making in marketing strategies, with a focus on actionable insights and continuous improvement through model iteration and evaluation.
