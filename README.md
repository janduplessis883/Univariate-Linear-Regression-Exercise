# Univariate-Linear-Regression-Exercise
```
                            **OLS Regression Results**                            
==============================================================================
Dep. Variable:           BRAIN_WEIGHT   R-squared:                       0.639
Model:                            OLS   Adj. R-squared:                  0.638
Method:                 Least Squares   F-statistic:                     416.5
Date:                Mon, 21 Nov 2022   Prob (F-statistic):           5.96e-54
Time:                        13:41:27   Log-Likelihood:                -1350.3
No. Observations:                 237   AIC:                             2705.
Df Residuals:                     235   BIC:                             2711.
Df Model:                           1                                         
Covariance Type:            nonrobust                                         
==============================================================================
                 coef    std err          t      P>|t|      [0.025      0.975]
------------------------------------------------------------------------------
Intercept    325.5734     47.141      6.906      0.000     232.701     418.446
HEAD_SIZE      0.2634      0.013     20.409      0.000       0.238       0.289
==============================================================================
Omnibus:                        8.329   Durbin-Watson:                   1.843
Prob(Omnibus):                  0.016   Jarque-Bera (JB):                8.665
Skew:                           0.366   Prob(JB):                       0.0131
Kurtosis:                       3.584   Cond. No.                     3.66e+04
==============================================================================

Notes:
[1] Standard Errors assume that the covariance matrix of the errors is correctly specified.
[2] The condition number is large, 3.66e+04. This might indicate that there are
strong multicollinearity or other numerical problems.
```
**Condition number** depends on the underlying norm. However, regardless of the norm, it is always greater or equal to 1. If it is close to one, the matrix is well conditioned which means its inverse can be computed with good accuracy. If the condition number is large, then the matrix is said to be ill-conditioned.<BR><BR>
**R-squared** is a goodness-of-fit measure for linear regression models. This statistic indicates the percentage of the variance in the dependent variable that the independent variables explain collectively. R-squared measures the strength of the relationship between your model and the dependent variable on a convenient 0 – 100% scale.<BR><BR>

The **t-value** measures the size of the difference relative to the variation in your sample data. Put another way, T is simply the calculated difference represented in units of standard error. The greater the magnitude of T, the greater the evidence against the null hypothesis.<BR><BR>
The **Pr(>|t|) column** represents the p-value associated with the value in the t value column.

If the **p-value** is less than a certain significance level (e.g. α = .05) then the predictor variable is said to have a statistically significant relationship with the response variable in the model.<BR><BR>
**P values and coefficients** in regression analysis work together to tell you which relationships in your model are statistically significant and the nature of those relationships. The linear regression coefficients describe the mathematical relationship between each independent variable and the dependent variable. The p values for the coefficients indicate whether these relationships are statistically significant.<BR><BR>

The **omnibus test** is a likelihood-ratio chi-square test of the current model versus the null (in this case, intercept) model. The significance value of less than 0.05 indicates that the current model outperforms the null model.<BR><BR>

Image result for linear regression **f statistic**
Summary. f-statistics is a statistic used to test the significance of regression coefficients in linear regression models. f-statistics can be calculated as MSR/MSE where MSR represents the mean sum of squares regression and MSE represents the mean sum of squares error.<BR><BR>
**Kurtosis** is a measure of the combined weight of a distribution's tails relative to the center of the distribution. When a set of approximately normal data is graphed via a histogram, it shows a bell peak and most data within three standard deviations (plus or minus) of the mean. However, when high kurtosis is present, the tails extend farther than the three standard deviations of the normal bell-curved distribution.<BR><BR>
**Types of Kurtosis**<BR>
There are three categories of kurtosis that can be displayed by a set of data. All measures of kurtosis are compared against a standard normal distribution, or bell curve.<BR>

**`Meoskurtic (kurtosis = 3.0)`**
The first category of kurtosis is a mesokurtic distribution. This distribution has a kurtosis statistic similar to that of the normal distribution, meaning the extreme value characteristic of the distribution is similar to that of a normal distribution.<BR>

**`Leptokurtic (kurtosis > 3.0)`**
The second category is a leptokurtic distribution. Any distribution that is leptokurtic displays greater kurtosis than a mesokurtic distribution. Characteristics of this distribution is one with long tails (outliers.) The prefix of "lepto-" means "skinny," making the shape of a leptokurtic distribution easier to remember. The "skinniness" of a leptokurtic distribution is a consequence of the outliers, which stretch the horizontal axis of the histogram graph, making the bulk of the data appear in a narrow ("skinny") vertical range.<BR>

Thus leptokurtic distributions are sometimes characterized as "concentrated toward the mean," but the more relevant issue (especially for investors) is there are occasional extreme outliers that cause this "concentration" appearance. Examples of leptokurtic distributions are the T-distributions with small degrees of freedom.
 While a leptokurtic distribution may be "skinny" in the center, it also features "fat tails".<BR><BR>
**`Platykurtic (kurtosis < 3.0)`**
The final type of distribution is a platykurtic distribution. These types of distributions have short tails (paucity of outliers.) The prefix of "platy-" means "broad," and it is meant to describe a short and broad-looking peak, but this is an historical error. Uniform distributions are platykurtic and have broad peaks, but the beta (.5,1) distribution is also platykurtic and has an infinitely pointy peak.<BR>

The reason both these distributions are platykurtic is their extreme values are less than that of the normal distribution. For investors, platykurtic return distributions are stable and predictable, in the sense that there will rarely (if ever) be extreme (outlier) returns.
