# Telecom-Customer-Churn
## To predict whether a current customer in a particular (unnamed) telecom company, will churn or not.


### Following steps are performed:
1) **EDA:** First we perform exploratory data analysis (EDA) to explore the data set and draw insights from the
            possible patterns that we can detect. [Refer to -> Customer churn analysis (Telecom Industry).ipynb]
   
2) **ML Modeling**: We experiment on varous machine learning models, in order to as much accurately predict as possible, the possibility
                    of a customer getting churned. [Refer to -> Churn analysis - model building.ipynb]
                    
3) **Upsampling and finalizing model**: The data we have here is unbalanced, we have much more data on customer that have not churned, than customers that have. To address this we utilize an upsampling process called SMOTE-ENN (Synthetic Minority Oversampling Technique- Edited Nearest Neighbor). We try various models and finalize the best performing ML model, on this upsampled dataset.

4) **App Building**: In order to deploy our model on the web, we use the Flask micro webframework (as backend) and HTML (as frontend). [Refer to -> flask_app.py]
