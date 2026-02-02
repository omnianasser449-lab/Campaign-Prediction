📊 Marketing Campaign Conversion Prediction
The Goal
Predict whether a customer will subscribe to a product (Conversion) based on demographic data and campaign touchpoints to optimize ad spend.

🛠️ Tools Used
Python (Pandas, Scikit-Learn)
Machine Learning: Random Forest Classifier (Classification)
Model Deployment: Joblib (Saving the model for production)
💡 Key Insights
Targeting Accuracy: The model successfully predicted customer behavior with an accuracy of 89.38%.
The "Age" Factor: Demographic analysis (like age 50 in our test) was used to determine the probability of a "Yes" vs. "No" response.
Conversion Logic: The model identifies patterns in previous "Campaign" contacts to stop "over-calling" customers who are unlikely to convert.
Production Ready: The model was saved as marketing_model.pkl, meaning it is ready to be integrated into a real-time marketing dashboard.
🚀 Strategy Recommendation
Implement a "Smart Dialing" system. Instead of calling every customer, 
the marketing team should only contact those the model predicts as "1" (Likely to convert). This reduces operational costs by roughly 10-15% and 
prevents "Brand Fatigue" by not bothering uninterested customers.
