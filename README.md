# Airplane Delay Prediction Project

This project predicts whether a flight will be delayed due to weather conditions. The solution is tailored for a travel booking website aiming to enhance customer experience by forecasting delays during flight bookings.

---

## Objectives

- **Business Problem**: Predict delays for the busiest U.S. airports to improve travel planning.
- **Dataset**: Historical flight performance data (2014-2018) with weather and holiday integrations.
- **Machine Learning Goal**: Binary classification to determine flight delay status (delayed vs. not delayed).

---

## Key Features

1. **Data Preprocessing**:
   - Processed and combined 60 CSV files from compressed datasets.
   - Filtered data for top airports and airlines to focus on high-traffic routes.

2. **Feature Engineering**:
   - Added **holiday indicators** and **weather data** (e.g., precipitation, wind speed, snow levels).
   - Encoded categorical variables using one-hot encoding.

3. **Model Training and Evaluation**:
   - **Baseline Model**: Logistic Regression.
   - Metrics:
     - **Accuracy**: 78.9%
     - **Precision**: 78% (delayed flights)
     - **Recall**: 100% (delayed flights)
     - **F1-Score**: 87.6%
   - Specificity increased by 3% after incorporating weather and holiday data.

4. **Visualization**:
   - Created insights with Tableau. View the [Dashboard](https://public.tableau.com/app/profile/akshay.kumar.ramesh/viz/AirplaneDelays_16989588080900/Dashboard1).

---

## Tech Stack

- **Programming**: Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Cloud Services**: AWS (EC2 for execution, S3 for dataset storage)
- **Visualization**: Tableau for business insights and presentation

---

## Results and Key Metrics


- **Metrics**:
- **Train Accuracy**: 79.0%
- **Test Accuracy**: 78.9%
- **Precision**: 78% (for delayed class)
- **Recall**: 100% (for delayed class)
- **Specificity**: 3% improvement after adding engineered features
- **F1-Score**: 87.6%

---

## Running Locally

1. Clone the repository:
 ```bash
 git clone https://github.com/Bane-24/Airplane-Delays.git
 cd Airplane-Delays
pip install -r requirements.txt
python delay_prediction.py

---

## Running on AWS
git clone https://github.com/Bane-24/Airplane-Delays.git
pip install -r requirements.txt
python delay_prediction.py

Future Improvements

Advanced Models: Implement XGBoost or Random Forest for better performance.
Additional Features: Integrate real-time weather and air traffic data.
Hyperparameter Tuning: Optimize logistic regression or explore ensemble techniques.



