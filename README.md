# Lahore AQI Prediction

Predicts Lahore's monthly Air Quality Index (AQI) from the previous month's AQI, month number, and smog, crop-burning and monsoon season flags.

**Data:** Pakistan Air Quality Index: 10 Cities, 2015–2025 (Kaggle), filtered to Lahore (132 months).

**Method:** Linear Regression in scikit-learn, trained on the first 80% of months and tested on the most recent 20%.

**Result:** Mean Absolute Error of about 7.4 AQI points on the test period.

**Key finding:** Smog season is the strongest driver of Lahore's AQI. Last month's AQI also carries over into the next month.

**Tools:** Python, Pandas, scikit-learn, Matplotlib, Google Colab
