# used-car-prices
Building a regression model to understand what features drives the used car prices

Summary

This report provides a data-driven analysis of the factors influencing used car prices. Our goal is to help used car dealers optimize their inventory by identifying the key drivers of price fluctuations. Using advanced regression models, we have determined the most impactful features affecting pricing and selected Ridge Regression as the most reliable model for predicting used car prices.

Key Findings

Top Factors Impacting Price

Year – Newer cars are priced significantly higher.

Mileage (Odometer Reading) – Higher mileage decreases value.

Title Status – Cars with a clean title sell for more, while salvage/rebuilt titles reduce resale value.

Condition – Cars listed as "excellent" or "like new" command higher prices than those marked as "fair" or "salvage."

Model Comparison & Selection

Evaluated three different regression models:

Polynomial Regression – Captures complex relationships but risks overfitting.

Lasso Regression – Simplifies the model by removing less impactful features but may omit valuable predictors.

Ridge Regression – Maintains key features while preventing overfitting, making it the best model for accurate price prediction.

Best Model Chosen: Ridge Regression

Actionable Insights for Dealers

Optimize Inventory Selection – Prioritize newer cars with lower mileage and a clean title to maximize resale value.

Pricing Strategy – Price vehicles competitively based on condition and title status, leveraging insights from our model.

Marketing & Sales Focus – Highlight low-mileage vehicles and well-maintained cars in listings to attract higher offers.

Negotiation Strategies – Use price-impact factors (e.g., salvage title, high mileage) as leverage when acquiring inventory.

Recommendations

Further Data Enrichment – Incorporate additional features like accident history, trim level, and market demand trends to make the model more accurate.

Conclusion

The insights from our analysis provide a clear roadmap for optimizing inventory and pricing strategies. By leveraging data-driven decision-making, dealers can enhance profitability and stay competitive in the used car market.