# Predictive-Modeling-for-Agriculture
This project uses Logistic Regression to predict the best crop based on soil conditions. By analyzing soil features like Nitrogen (N), Phosphorous (P), Potassium (K), and pH levels, the model helps farmers make data-driven decisions about crop cultivation.

#Approach
The dataset soil_measures.csv includes soil nutrient levels (N, P, K, pH) and the corresponding crop type.
We evaluate each feature (N, P, K, pH) individually using Logistic Regression to determine its predictive power.
The Potassium (K) content emerged as the most predictive feature for determining crop type, with an accuracy score of 26.67%.
Conclusion
Potassium (K) is identified as the key predictor for crop type in this dataset. Further improvements can be made by using all features together and exploring more complex models.

#Technologies Used
Python, Pandas, NumPy, scikit-learn
