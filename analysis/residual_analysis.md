\# Residual Analysis



\## Predicted Sales



Predicted monthly sales were calculated using the final multiple linear regression model. These values represent the sales estimated by the model based on the selected independent variables.



\## Residual Calculation



Residual = Actual Monthly Sales − Predicted Monthly Sales



\- A \*\*positive residual\*\* means the actual sales were higher than the model predicted (under-prediction).

\- A \*\*negative residual\*\* means the actual sales were lower than the model predicted (over-prediction).



\## Top 5 Largest Positive Residuals



| Observation | Predicted Monthly Sales | Residual |

|------------:|------------------------:|---------:|

| 316 | 797340.7360 | 47369.9340 |

| 315 | 686151.8765 | 26223.8935 |

| 318 | 520559.2674 | 16286.1526 |

| 320 | 557781.5885 | 1879.2515 |

| 319 | 726187.1858 | 589.0342 |



\## Top 5 Largest Negative Residuals



| Observation | Predicted Monthly Sales | Residual |

|------------:|------------------------:|---------:|

| 4 | 734601.4102 | -75681.1102 |

| 5 | 788326.9753 | -46985.5353 |

| 2 | 679032.8824 | -44596.8824 |

| 1 | 677155.8840 | -18323.2640 |

| 3 | 696319.0938 | -17597.0338 |



\## Business Interpretation



The observations with the largest positive residuals performed better than the model predicted. These stores may have benefited from factors not included in the dataset, such as local promotional campaigns, seasonal demand, customer loyalty, or better operational efficiency.



The observations with the largest negative residuals performed below the model's prediction. Possible reasons include inventory shortages, operational inefficiencies, stronger local competition, temporary market conditions, or other external factors that were not captured by the model.



\## Model Performance



The residuals contain both positive and negative values, indicating that the model does not consistently over-predict or under-predict monthly sales. Most residuals are reasonably close to zero, suggesting that the multiple regression model provides a good overall fit. However, the presence of a few large residuals indicates that additional variables or external business factors may further improve the model's predictive accuracy.

