# 🎬 Oscar Award Prediction Using Machine Learning

Overview
This project explores the use of machine learning classification models to predict whether a movie will win an Oscar award. A Decision Tree Classifier was used as the baseline model, followed by performance improvement attempts using ensemble methods and hyperparameter tuning.

The project demonstrates key machine learning concepts including model training, evaluation, and ensemble learning techniques.

Dataset
- Source: Provided in-class dataset by Start tech Academy 
- Size: 506 entries, 18 features  
- Target variable: `Start_Tech_Oscar` (Binary classification)

Preparation:
- Handled missing values
- Cleaned dataset for modeling
- No feature scaling or transformation was applied

Tools & Liabraries used
- Python  
- Jupyter Notebook  
- Scikit-learn  
- XGBoost  
- Pandas  
    

Model Development

Baseline Model
- Model: Decision Tree Classifier  
- Train-test split applied before training  
- Initial accuracy: **54%**

Model Optimization
To improve performance, the following techniques were applied:

- GridSearchCV for hyperparameter tuning  
- Ensemble methods (including boosting techniques such as XGBoost)  
- Cross-validation for model evaluation stability  

Model Performance
Baseline Decision Tree:54% 
Tuned + Ensemble Models:62% 

Despite multiple optimization attempts, the model performance capped at 62% accuracy.

Key Evaluation Tools
The following evaluation methods were used:

- Confusion Matrix (frequently used for classification evaluation)
- Feature Importance analysis (using XGBoost)
- Decision Tree visualization

Key Insights
- Model performance improved slightly after applying ensemble techniques and hyperparameter tuning.
- However, accuracy capped at 62%, suggesting potential **underfitting or limited predictive signal in the dataset**.
- Feature relationships were not strong enough for high predictive accuracy using tree-based models alone.
- Ensemble methods provided more stability but not a major accuracy boost.


 Visualizations used:
- Decision Tree diagram
- Confusion matrices
- Feature importance plots (XGBoost)


 Conclusion
This project demonstrates that while decision trees and ensemble methods can improve performance, model accuracy is ultimately constrained by the quality and predictive power of the dataset, which leads me to a conclusion that perhaps with a larger datasets results may become better.

 Future Improvements
- Testing other classification models.

 Author
Tebogo Mosehle
