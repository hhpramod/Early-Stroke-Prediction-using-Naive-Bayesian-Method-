# Early-Stroke-Prediction-using-Naive-Bayesian-Method-

# Introduction
Stroke is a serious global health issue that affects people everywhere, regardless of where they live or their background. It happens when something disrupts the flow of blood to the brain, causing harm and, in many cases, leading to death. Shockingly, it stands as the second leading cause of death worldwide, making up about 11% of all recorded deaths, according to the World Health Organization (WHO).
What makes stroke particularly challenging is that it happens quietly inside the complex structure of the brain. Unlike some other health emergencies, it requires quick and accurate action for the best possible results.
Detecting stroke early is crucial for effective treatment, as it helps stop the chain of events triggered by the interruption of blood flow. This project is all about using advanced statistical methods called Bayesian techniques to improve the early identification of stroke.


# Data set description
This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. The attribute information is given as follows. (data source: https://www.kaggle.com/code/ashokkumarpalivela/stroke-prediction-end-to-end-project/input)

# Statistical Method
This study employs Bayesian techniques, specifically Naive Bayesian Classifier to identify early signs of stroke. The Naive Bayesian approach assumes independence between predictors, providing a straightforward initial assessment of the individual impact of each variable. Bayesian multiple linear regression, on the other hand, considers the relationships between multiple predictors, offering a more nuanced understanding of their combined influence on the likelihood of a stroke.

# Dealing with/Overcoming Assumption Violations
To address potential violations of assumptions, such as normality of residuals in linear regression, we utilize Bayesian methods that are inherently robust and less reliant on strict assumptions. Bayesian statistics, by nature, allows for more flexibility in modeling complex relationships without being overly constrained by assumptions that may not hold in real-world scenarios.

# Detailed Procedure
The procedure that I have to deal can be state as follows. There I have included all the steps from data preprocessing to model evaluation.
