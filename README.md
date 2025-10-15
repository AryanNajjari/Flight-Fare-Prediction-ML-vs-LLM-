# Flight-Fare-Prediction-ML-vs-LLM-
Predicting flight fares using traditional machine learning models (Linear Regression and Random Forest) and a fine-tuned LLM (GPT-4o-mini), with visualization and metrics-based performance evaluation.

**Data Source:** https://www.kaggle.com/datasets/vivekgediya/flight-dataset 

Results' summary: (Visual Results are uploaded in the "Results" folder. 

| Model             |   MAE   |     MSE    |   RMSE   |  R²   |
| ----------------- | ------- | ---------- | -------- | ----- |
| Linear Regression | 1684.08 | 5363530.52 | 2315.93  | 0.700 |
| Random Forest     | 1124.68 | 3613562.53 | 1900.94  | 0.798 |
| GPT-4o-mini       | 1671.45 | 6693850.15 | 2587.25  | 0.630 |


Although the GPT-4o Mini demonstrates lower predictive accuracy based on the metrics, it is important to note that this evaluation was conducted using only **400 training data points**, whereas traditional ML methods were trained on more than 8,000 data points. 
