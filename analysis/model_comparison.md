\# Model Comparison



\## Objective



The objective of this analysis is to compare the performance of the Simple Linear Regression model and the Multiple Linear Regression model in predicting monthly sales for retail stores.



\---



\## Model Overview



\### Simple Linear Regression



\* \*\*Dependent Variable:\*\* Monthly Sales

\* \*\*Independent Variable:\*\* Footfall



\### Multiple Linear Regression



\* \*\*Dependent Variable:\*\* Monthly Sales

\* \*\*Independent Variables:\*\*



&#x20; \* Marketing Spend

&#x20; \* Footfall

&#x20; \* Average Discount Percentage

&#x20; \* Staff Count

&#x20; \* Inventory Availability Percentage

&#x20; \* Competitor Distance

&#x20; \* Holiday Flag

&#x20; \* Customer Rating

&#x20; \* Region (Dummy Variables)

&#x20; \* Store Type (Dummy Variables)



\---



\## Performance Comparison



| Metric            | Simple Linear Regression | Multiple Linear Regression |

| ----------------- | -----------------------: | -------------------------: |

| Observations      |                      319 |                        320 |

| Multiple R        |                    0.859 |                      0.926 |

| R Square          |                    0.738 |                      0.857 |

| Adjusted R Square |                    0.737 |                      0.850 |

| Standard Error    |                   53,249 |                     40,158 |

| Significance F    |                 2.74E-94 |                  1.50E-119 |



\---



\## Interpretation



The Simple Linear Regression model explains approximately \*\*73.8%\*\* of the variation in monthly sales using only \*\*Footfall\*\* as the predictor.



The Multiple Linear Regression model explains approximately \*\*85.7%\*\* of the variation in monthly sales by incorporating marketing, operational, customer, regional, and store-type variables.



The Multiple Linear Regression model has:



\* Higher R Square

\* Higher Adjusted R Square

\* Lower Standard Error

\* Better overall predictive performance



\---



\## Conclusion



The \*\*Multiple Linear Regression\*\* model performs better than the Simple Linear Regression model because it captures the combined effect of multiple business factors influencing monthly sales.



Based on the evaluation metrics, the Multiple Linear Regression model is recommended for sales prediction and business decision-making.



