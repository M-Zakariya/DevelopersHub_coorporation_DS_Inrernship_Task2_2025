**Task 1**: Term Deposit Subscription Prediction (Bank Marketing)

**Task Objective**:
                  Predict whether a bank customer will subscribe to a term deposit as a result of a marketing campaign.


**My Approach**:
                Dataset Loading
                EDA(Exploratory Data Analysis)
                Feature Encoding
                Data Visualization
                Model development/Training
                Model Evaluation
                Interpretability (SHAP)

**Result and finding**:
                      The models (Logistic Regression and Random Forest) performed reasonably well, with ROC-AUC values of 0.90 and 0.91, respectively.

                      The most important features were age, balance, duration, and previous campaign outcomes.

  **SHAP explanations showed:**

                              For individuals → predictions were influenced by personal financial attributes (balance, duration, previous contact).

                              Globally → age and balance were key drivers, especially when interacting together.

**Business insight:** Customers with higher age and higher balance are more likely to subscribe. This can guide targeted marketing campaigns.

