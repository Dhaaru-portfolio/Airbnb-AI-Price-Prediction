# 🏠 NYC Airbnb Price Prediction | AI + Machine Learning

> Predict Airbnb rental prices in New York City using 48,895 listings and Machine Learning.

### 🎯 Business Problem:
How much should a host charge for their property? Analyzed price difference between Manhattan vs Brooklyn and built an AI model to suggest optimal pricing.

### 📊 Dataset:
- Source: NYC Airbnb Open Data (Inside Airbnb)
- 48,895 listings | 16 features
- Features: Location, Room Type, Reviews, Availability, Host Data

### 🔍 Key Insights:
- Manhattan avg price: $196 vs Brooklyn: $124 (58% difference)
- Entire home/apartment earns 2.5x more than shared room
- Properties with 100+ reviews can charge 30% premium

### 🤖 Model Built:
- Algorithm: Random Forest Regressor + XGBoost
- Accuracy: R2 Score 0.81
- Features used: neighbourhood_group, room_type, minimum_nights, number_of_reviews, availability_365

### 🛠️ Tech Stack:
Python, Pandas, Scikit-Learn, Matplotlib, Seaborn, Google Colab

### 📈 Visuals Included:
- Price distribution by borough
- Room type vs price
- Top 10 expensive neighbourhoods
- Feature importance chart

### 🚀 How to Run:
```python
pip install pandas scikit-learn
python model.py
