# Final_retail_sales_forecast

This project involves:

**Store**: Identifier for the store where the sales occurred.

**Dept**: Identifier for the department within the store.

**Weekly_Sales**: Total sales for the week (target variable).

**IsHoliday**: Indicator of whether the week is during a holiday season (binary).

**Type**: Type of store (e.g., A, B, C) which could denote different formats or categories.

**Size**: Size of the store, typically in square feet.

**Temperature**: Average temperature during the week (likely in degrees Fahrenheit).

**Fuel_Price**: Average price of fuel during the week.

**MarkDown1 to MarkDown5**: Discount amounts for different promotions or markdowns (e.g., for different products or categories).

**CPI**: Consumer Price Index, a measure of inflation or the cost of living.

**Unemployment**: Unemployment rate during the week.

**year**: Year of the observation.

**month**: Month of the observation.

**day**: Day of the observation.

**week**: Week number of the year for the observation.

Each column represents a different aspect of the sales data, with some columns providing temporal context, others indicating store and department characteristics, and additional columns related to external factors like holidays, pricing, and economic indicators.

Here in this project we are predicting weekly sales with regression Machine learning  model ,  The Random Forest Regressor exhibits high R² scores and low error metrics for both training and test data, suggesting that it performs well and generalizes effectively to unseen data.

**Generalization**: It shows less evidence of overfitting compared to the Decision Tree, which has a perfect R² score on training data but also high performance on testing data. The Random Forest’s performance on both datasets is very close, indicating robust generalization.

**Error Metrics**: Compared to other models, the Random Forest has the lowest testing error metrics (MSE, RMSE, MAE), indicating fewer prediction errors on unseen data.
In summary, the Random Forest Regressor provides a good balance between accuracy and generalization, making it the best choice among the models listed.

