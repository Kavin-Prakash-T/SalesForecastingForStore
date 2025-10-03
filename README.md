#  Sales Forecasting Web App

A Flask-based web application that predicts **third-month sales** for a store/product using **Linear Regression**.  
The app takes sales data from the first two months and forecasts sales for the third month, helping store owners make better inventory and business decisions.

---

##  Features
-  Predict third-month sales using first and second month values.
-  Preloaded dataset with sample sales data.
-  Data preprocessing (handles missing values & categorical ratings).
-  User-friendly Flask web interface.
-  Easy to extend with more features like promotions, holidays, or time-series forecasting.

---

## 📊 Dataset

Example dataset (`sales.csv`):

```csv
rate,sales_in_first_month,sales_in_second_month,sales_in_third_month
,2,500,300
,4,300,650
four,600,200,400
nine,450,320,650
seven,600,250,350
five,550,200,700

