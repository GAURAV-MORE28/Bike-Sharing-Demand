Overview: Predict daily bike rentals (cnt) from weather/date features.

Data Processing: date parsing; engineered seasonal features; categorical encoding; imputations.

Models: Linear, Ridge (tuned), Random Forest (tuned), Gradient Boosting (tuned) with TimeSeriesSplit.

Evaluation: MAE, RMSE, R² on chronological hold-out; Actual vs Predicted plot.

Brownie Points: two models for casual and registered, summed to cnt.

Conclusion: best model + why; top drive
