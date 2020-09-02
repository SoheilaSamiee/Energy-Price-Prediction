# HydroQubec-Price-Prediction

The goal of the project is "Predicting the Hourly Ontario Energy Price (HOEP) in the medium and long term". Data is provided by the Hydro-Québec energy trading floor in the Tenth Montreal Industrial Problem Solving Workshop.

# Description: 
"Predicting the electricity spot price on various Hydro-Québec export markets is a crucial part of the activities of its energy trading floor. The sales planning team uses the spot price to model the evolution of the sales volume (and the resulting revenue) over medium-term and long-term horizons.
Predicting the spot price on the Ontario market is especially difficult because of the characteristics of this market and the variables affecting the spot price.
(a) 12 percent of the Ontario energy production is wind-based and wind energy is an intermittent resource.
(b) Ontario has many fixed-price supply contracts.
(c) There is a lot of uncertainty in the demand forecast by the Ontario market manager.
A large fraction of Hydro-Québec exports are sold to Ontario. Modelling the hourly price is difficult: hence there is a discrepancy between the long-term forecast of sales and the actual sales volume." *

*: details provided by Hydro Quebec trading floor.

# Project:
In the current project classical machine learning approaches including Linear Regression, Elastic Net, Lasso, MLP, and gradient boosting are used for building a model that can predict ontario energy price using 18 months prediction parameters. The goal was to beat the currently available benchmark used by trading floor. As shown in the results section, Gradient Boosting could predict the price (called HOEP) better than bench mark. 

- Data is available in "Data_18months_Outlook" folder: 22 18-month prediction excel files.
- The main code is called: HQ-IPSW_PricePrediction_ClassicalMachineLearning.
- Results are available in "Result_files" folder.
