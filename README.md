# Sales Analysis and Forecasting with Deep Learning & Random Forest

This project performs end-to-end analysis of e-commerce sales data including:
- Exploratory Data Analysis (EDA)
- Shipping delay analysis by sub-category
- Outlier capping using IQR
- Time-based sales visualization (line plots, heatmaps)
- Sales prediction using both:
  - Deep Learning (TensorFlow/Keras)
  - Random Forest Regression (scikit-learn)

## 📊 Features
- Converts order and shipping dates to `datetime` format
- Adds year/month columns for time analysis
- Identifies and visualizes shipping delays > 5 days
- Clips extreme sales outliers using IQR
- Visualizes:
  - Monthly/yearly trends
  - Heatmaps
  - Category-wise bar plots
- Builds and evaluates:
  - Deep Learning regression model
  - Random Forest model


## 🧠 ML Models
- **Deep Learning**: 2 hidden layers with ReLU, trained using Mean Squared Error.
- **Random Forest**: 100 estimators with R² and MAE evaluation.

## 🛠 Requirements

Install packages using:
```bash
pip install -r requirements.txt
