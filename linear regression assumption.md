# Assumption of linear regression:


Linear regression is a widely used statistical method for modeling the relationship between a dependent variable and one or more independent variables. it is based on several assumptions that must be met in order for the results to be considered valid. we will examine these assumptions and the implications of not meeting them.

---

▶ Linearity: 

* This assumption states that there is a linear relationship between the independent and dependent variables.
* The relationship should be expressed as a straight line on a scatter plot, and the residuals (the difference between the actual and predicted values) should be randomly dispersed around zero.
* If this assumption is violated, the regression results may be misleading and the model will not generalize well to new data.

---

▶ Independence:

* The observations in the data should be independent of each other, meaning that the value of one observation should not affect the value of another observation.
* If the observations are dependent, the standard errors of the regression coefficients will be biased and the results will not be valid.

---

▶ Homoscedasticity:

* `hemoscedasticity` means that variance should not be increasing or decreasing (constant) if error term changes (increase or decrease). Also it should not be following some pattern as error term changes (increase or decrease).
* `Heteroskedasticity` refers to the situation where the variance of the residuals in a regression model is not constant across different levels of the predictor variables.
* To dentify heterscedasticity , we will use statistical test called `breusch-pagan`. this test check whether heterscedasticity exists or not.
* The null hypothesis of the test is that the variance of the residuals is constant (homoscedastic), while the alternative hypothesis is that the variance of the residuals is not constant (heteroskedastic).

---

▶ Normality:

* The residuals should be normally distributed.
* This assumption is important for hypothesis testing and confidence interval construction, as well as for the validity of certain statistical models. If the residuals are not normally distributed, the regression results may not be accurate.
* To identify normality of residuals plot the histogram of the error terms.

---

▶ mean of residuals

* Mean of residuals should be equal zero.

---

▶ Error Term should be independent to each other

* It means that the error term should not dependent in any other error terms.
* Scatter plot of residuals and y_predection (error terms diagram) should be randomly distributed and not following any pattern.

---

▶ multicollinearity:

* The independent variables should not be highly correlated with each other. 
* To check this issue we can plot the pairwise correlation plot and avoid using high correlated variables.
* Also you can check about multicollinearity by VIF (Variance Inflation Factor).
* VIF value ranges between 1 to infinity . value 1 indecation no multicollinearity and the higher value of VIF , the higher value of multicollinearity.

   * VIF between 1:5 indecating moderate multicollinearity.
   * VIF between 5:10 indecating higher level of multicollinearity.
   * VIF between 10:.. indecating very high level multicollinearity. 

* Variables with high VIF values are likely to be highlt correlated with one or more of other independent variabels, and may need to be removed or combined with other variables to reduce multicollinearity.




> It is important to check the assumptions of linear regression before using it to model data. If any of the assumptions are violated, the results may not be accurate, and alternative methods or data transformations may need to be used. There are various statistical tests and methods for checking the assumptions, including residual plots, normality tests, and variance inflation factors.
