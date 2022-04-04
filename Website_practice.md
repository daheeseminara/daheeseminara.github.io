# Module 4 Notes - 5.2.3 and 5.2.4

## 5.2.3. Goodness of Fit

The **goodness of fit** describes how well a model explains the given data by computing R^2 using the two below: 
* Total sum of square (TSS)
* Sum of squared errors (SSE)

**R^2 = 1 - SSE / TSS**
* The fraction of variation in y that a model _**can**_ explain
* Always between 0 and 1

### Steps

**Step 1:** TSS: get a total sum of squares, which captures the total amnount of variation in y around its mean ybar
**Step 2:** SSE: get a sum of squared errors, which captures the total amount of errors in the predictions (the closer it is to zero, the better)
**Step 3:** SSE/TSS: returns the fraction of variation in y that a model **cannot** explain
**Step 4:** R^2 equals 1 minus SSE/TSS which is the fraction of variation in y that a model **can** explain

## 5.2.4. Interpreting Regression Coefficients

**Generic Interpretation of Coefficients**

1. A 1 unit increase in Xi... 
2. ... is associated with a bi change in y... 
3. holding all other X constant 

- Log transformations are useful - because they model **proportional** relationships 

- Categorical or qualitative variable with two values - usually encode one value as zero and the other as one before including in the regression 

- The interpretation of beta(one level of a categorical variable) is the same as a binary variable, except that it is capturing the jump from the "omitted group" (X = 0 above) to whichever level that particular beta captures

- always keep the "holding all other controls constant"

- Key (or helpful tips) to interpreting coefficients is to find the applicable model in 5.2.4.3 and the meanings

