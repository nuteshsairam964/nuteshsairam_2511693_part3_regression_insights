\# Model Equations



\## 1. Simple Linear Regression Equation



The simple linear regression model is:



\*\*Monthly Sales = 446190.52 + (35.75 × Footfall)\*\*



\### Interpretation



\- \*\*Intercept (446190.52):\*\* If footfall is zero, the model predicts monthly sales of approximately ₹446,191. Although this situation is unrealistic, the intercept provides the baseline value of the model.



\- \*\*Footfall Coefficient (35.75):\*\* For every one additional customer visiting the store, monthly sales are expected to increase by approximately \*\*₹35.75\*\*, assuming all other factors remain constant.



\---



\## 2. Multiple Linear Regression Equation



The final multiple regression model is:



\*\*Monthly Sales =\*\*



42075.50



\+ (1.2077 × Marketing Spend)



\+ (27.3789 × Footfall)



− (41697.72 × Average Discount %)



\+ (3481.73 × Staff Count)



\+ (3060.22 × Inventory Availability %)



− (3423.81 × Competitor Distance)



\+ (15077.63 × Holiday Flag)



\+ (12522.22 × Customer Rating)



\+ (9933.27 × Region\_North)



\+ (21047.24 × Region\_South)



\+ (25258.37 × Region\_West)



\+ (44678.63 × Store\_Airport)



\+ (20381.72 × Store\_HighStreet)



\+ (32866.45 × Store\_Mall)



\---



\## 3. Interpretation of Coefficients



\- \*\*Marketing Spend:\*\* Every additional ₹1 spent on marketing increases monthly sales by approximately \*\*₹1.21\*\*, holding other variables constant.



\- \*\*Footfall:\*\* Each additional customer increases monthly sales by approximately \*\*₹27.38\*\*.



\- \*\*Average Discount Percentage:\*\* Higher discounts reduce predicted monthly sales by approximately \*\*₹41,698\*\* for every one-unit increase in discount percentage, indicating excessive discounts may reduce revenue.



\- \*\*Staff Count:\*\* Each additional staff member is associated with an increase of approximately \*\*₹3,482\*\* in monthly sales.



\- \*\*Inventory Availability:\*\* A one-unit increase in inventory availability percentage increases monthly sales by approximately \*\*₹3,060\*\*.



\- \*\*Competitor Distance:\*\* Stores located farther from competitors tend to have slightly lower predicted monthly sales according to this model.



\- \*\*Holiday Flag:\*\* Holiday periods increase monthly sales by approximately \*\*₹15,078\*\* compared with non-holiday periods.



\- \*\*Customer Rating:\*\* Every one-point increase in customer rating increases monthly sales by approximately \*\*₹12,522\*\*.



\---



\## 4. Dummy Variables



Categorical variables were converted into dummy variables before regression analysis.



\### Region Dummy Variables



\- Region\_North

\- Region\_South

\- Region\_West



\*\*Reference Category:\*\* East



\### Store Type Dummy Variables



\- Store\_Airport

\- Store\_HighStreet

\- Store\_Mall



\*\*Reference Category:\*\* Residential



The coefficients of dummy variables represent the expected difference in monthly sales compared with their respective reference category.



\---



\## 5. Reference Categories



\*\*Region Reference:\*\* East



\*\*Store Type Reference:\*\* Residential



\---



\## 6. Final Model Selected



The \*\*Multiple Linear Regression model with dummy variables\*\* was selected as the final model.



\---



\## 7. Reason for Selecting the Final Model



The multiple regression model explains monthly sales more effectively because it considers multiple business factors simultaneously, including marketing activities, customer traffic, inventory availability, customer ratings, holidays, regional differences, and store types.



The model achieved:



\- \*\*Multiple R = 0.9256\*\*

\- \*\*R² = 0.8568\*\*

\- \*\*Adjusted R² = 0.8502\*\*



These values indicate that the model explains approximately \*\*85.68%\*\* of the variation in monthly sales, making it substantially stronger than the simple regression model (R² = 73.83%).



Therefore, the multiple regression model provides more accurate predictions and more meaningful business insights for decision-making.

