# Risk-Assessment-for-home-credit-applicants
Perform risk assessment for home credit applicants using machine learning techniques. Develop a predictive model to analyze applicant data, including financial information and credit history. Provide a comprehensive evaluation of creditworthiness to minimize default risks.



# Home Credit Default Risk (HCDR) Kaggle Competition

This project aims to develop a well-optimized and efficient machine learning model to assess the risk of home credit default for lenders. By analyzing factors such as credit history, occupation, age, location, and credit card usage, we provide decision-making guidance for sustainable business operations.

## Project Phases

### Phase 1
In this phase, we implemented baseline models (Logistic Regression and Random Forest) using features from three out of eight available datasets. We conducted four experiments and will present the results in the following sections. Our goal is to create a predictive model that enables Home Credit to predict repayment likelihood accurately.

### Phase 2
We focused on improving test accuracy by employing feature engineering, hyperparameter tuning, feature selection, and ensemble methods. XGBoost, AdaBoost, and LightGBM achieved a test accuracy of 0.76 with 66 features. LightGBM, after tuning, showed slight improvement with a 0.765 AUC. Feature engineering and hyperparameter tuning played a crucial role in achieving better results. We will compare the outcomes of phases I and II.

### Phase 3
In this phase, we extended our experiments by implementing hyperparameter tuning on XGBoost, AdaBoost, and Gradient Boost algorithms to determine the best test accuracy. We also fine-tuned data with a Neural Network, adjusting parameters such as epochs, learning rate, batch size, and optimizers. Our Neural Network model achieved a test AUC of around 74%. However, the LightGBM_Tuned model remained the best with a training time of 10 seconds, a test AUC of 76%, and a Kaggle submission score of 0.75. Future work involves further tuning the Neural Network model and exploring additional feature engineering techniques.

