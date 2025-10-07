# Car Price Prediction
A machine learning pipeline to predict used car selling prices based on vehicle attributes like age, mileage, condition, and brand tier. Built using Python and XGBoost, with hyperparameter tuning via Grid Search and business storytelling designed for Power BI dashboard integration.

# Project Highlights
- Cleaned and engineered features from raw vehicle listings
- Trained XGBoost model with Grid Search optimization
- Achieved MAE ≈ ₹3,400, RMSE ≈ ₹4,600, and R² ≈ 0.64
- Residual analysis and feature importance interpretation
- Exported predictions and metrics for the Power BI dashboard

# Business Use Cases
- Dealerships: Set competitive prices based on vehicle attributes
- Buyers: Understand fair value and negotiate confidently
- Sales Teams: Simulate pricing scenarios using Power BI

# Modeling Approach
- Feature engineering: age, mileage, condition bins, luxury brand flags
- Grid Search over XGBoost parameters (max_depth, learning_rate, n_estimators, etc.)
- Residual diagnostics and feature importance analysis
- Export-ready predictions for dashboard integration

# Power BI Integration
- Actual vs Predicted scatter plot
- Residual distribution by segment
- Feature importance breakdown
- Scenario simulation panel for dynamic pricing

# Requirements
- Python 3.8+
- pandas, numpy, scikit-learn, xgboost, matplotlib, seaborn
