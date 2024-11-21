# Exploratory Data Analysis (EDA) and Customer Churn Prediction in Music Streaming Service
# Description
This project focuses on analyzing customer churn in a music streaming service, with an emphasis on understanding the relationship between music preferences and cancellations. 
Using exploratory data analysis (EDA) and data preprocessing techniques, the project explores customer behavior and trends related to subscription plans, audio preferences, and cancellation patterns. 
The primary goal is to identify significant factors contributing to customer churn and prepare the data for predictive modeling.

# Key Objective:
Customer Churn Analysis: Investigate the factors influencing customer churn, especially focusing on the role of music preferences in cancellation decisions.
# Dataset Overview:
The dataset contains details about customers, their subscription plans, audio consumption behavior, and cancellations. Key features include:

Customer Information: Customer ID, Customer Name, Email, Member Since
Subscription Data: Subscription Plan, Subscription Rate, Discount Information, Cancellation Date
Audio Consumption: Session ID, Audio Order, Audio ID, Audio Type ID, Genre, Popularity
# Key Insights:
Pop Music and Churn: One of the key findings of the analysis is that a decrease in listening to pop music correlates with an increase in customer cancellations. 
This suggests that customers who previously enjoyed pop music may be more likely to cancel their subscription as their interest in this genre decreases.
Subscription Plans and Churn: The project explores how different subscription plans, pricing models, and discounts influence the likelihood of customers canceling their subscriptions.
Customer Activity: Analysis of customer activity (e.g., audio orders, frequency of use) helps determine how engaged users are and whether a decline in usage or activity is a precursor to churn.
Steps Involved:
# Data Exploration and Cleaning:

Data is preprocessed to ensure all columns are non-null, and relevant features are extracted for churn prediction.
Exploratory data analysis is performed to visualize relationships between features such as subscription plans, genres, and churn rates.
# Feature Engineering:

New features are created, such as customer tenure (how long customers stay before cancellation) and average subscription rate.
The relationship between audio preferences (e.g., genre popularity) and churn is thoroughly analyzed.
Data Preparation for Modeling:

The cleaned data is aggregated into a single table, combining all relevant customer data and features that influence churn.
The dataset is prepared for predictive modeling, which will later help in building a churn prediction model.
Tools and Technologies Used:
Programming Language: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
Environment: Jupyter Notebook
# Conclusion:
The findings, including the insight about pop music and churn, provide actionable data for improving customer retention strategies. 
By understanding customer preferences and the factors that lead to churn, the music streaming service can tailor content, subscriptions, and offers 
to reduce cancellations and improve customer loyalty. This project lays the groundwork for building accurate churn prediction models using machine learning techniques.
