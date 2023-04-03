# Classification-Engine-Banking
Churn and Non-Churn Customer Classification

Introduction: Modern customer analytics and personalization systems use a wide variety of methods that help to reveal and quantify customer preferences and intent, making marketing messages, ads, offers, and recommendations more relevant and engaging. However, most of these methods are designed to optimize only one immediate interaction with a customer and use objective functions defined through metrics like a click-through rate (CTR) or conversion rate (CR). This problem can be particularly important in industries like retail banking and telecom where customer relationships evolve over long periods of time.

Problem Statement: Create High Performing Classification Engine(Which Classifies Churn customer or non-churn customer based on data provided).
Churn customers are those who left the bank. Non-Churn customers are those who stick with a bank by being a customer.
My approach to solve the problem: Data cleaning, this is one of the main steps in every project. In this dataset, initially I cleaned the date columns, I separated year month and day into different columns. As there are no categorical values in the dataset. The status column has active and non-active which I replaced with 1 and 0. There are no null values in the dataset.
•Splitted the data into X and y  and using sk-learns train test split method, I splitted the data into the training and testing one. 
•After this step I used different classification models to train and predict on data. I used a random forest classifier, SVM, and ada boost classifier. Among this the best model was the ada boost classifier with 88%.
