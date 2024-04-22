# <div align="center">Housing Price Data Deep Analysis and Model Building and Model Selection</div>
<div align="center">
  <img src="readme_md_src_img\Designer.png" alt="Designer" width="500"/>
</div>

* Dataset is avaliable in artifacts folder.
* Analysis and model building is done in main.ipynb which is present in research folder.

## Project-Description
----------------------

A house value is simply more than location and square footage. Like the features that make up a person, an educated party would want to know all aspects that give a house its value. For example, you want to sell a house and you don’t know the price which you may expect — it can’t be too low or too high. To find house price you usually try to find similar properties in your neighborhood and based on gathered data you will try to assess your house price. 

The dataset comprises a diverse range of features essential for predicting house prices, including:

Property Features: Number of bedrooms, bathrooms, square footage of living and lot areas, total floors, condition, quality, basement square footage, year built, year renovated, and more.
Location Details: Zip code, latitude, and longitude coordinates.
Market Indicators: Variables such as coastal view, property viewings, and more.
Model Selection

Several regression algorithms are explored and evaluated to identify the most suitable model for house price prediction. The models considered include:

Linear Regression
Random Forest Regression
Support Vector Regression
XGBoost Regression

Evaluation Metrics

The performance of each model is assessed using metrics such as R-squared value, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE). These metrics provide insights into the accuracy, precision, and generalization capabilities of the models.

Optimal Model Selection
After thorough experimentation and cross-validation, the XGBoost Regression model emerges as the optimal choice, demonstrating the highest R-squared value of 88.46%. This model effectively captures the complex relationships between the predictor variables and the target variable, resulting in superior predictive performance.

Implications for Business
The deployment of the optimized house price prediction model offers several strategic advantages for stakeholders in the real estate industry:

Accurate Pricing: Enables precise estimation of property values based on comprehensive features, aiding sellers in setting competitive prices and maximizing profitability.
Market Insights: Provides valuable insights into market trends, preferences, and factors influencing property prices, facilitating informed decision-making and strategic planning.
Risk Management: Assists in assessing and mitigating risks associated with real estate investments by identifying potential discrepancies between predicted and actual prices.
Enhanced Customer Experience: Promotes transparency and fairness in transactions, enhancing customer satisfaction and trust in the real estate services provided.