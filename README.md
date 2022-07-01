# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
![deliverable_one](https://github.com/dgeroux/MechaCar_Statistical_Analysis/blob/main/deliverable_one.png)

**1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**
The coefficients that provided a non-random amount of variance to the mpg values are vehicle length, ground clearnace and the intercept. In other words, vehicle length and ground clearance have a signigicant impact on mpg. When an intercept is statistically significant, it means that the intercept term explains a significant amount of variability in the dependent variable (mpg) when all independent vairables are equal to zero. Depending on our dataset, a significant intercept could mean that the significant features (such as vehicle length and ground clearance) may need scaling or transforming to help improve the predictive power of the model. Alternatively, it may mean that there are other variables that can help explain the variability of our dependent variable that have not been included in our model. Depending on the dataset and desired performance of the model, you may want to change your independent variables and/or transform them and then re-evaluate your coefficients and significance.

**2. Is the slope of the linear model considered to be zero? Why or why not?**
The slope of the linear model is NOT considered to be zero.

In hypothesis testing, the **null hypothesis** is generally the hypothesis that can be explained by random chance and the **alternate hypothesis** is generally the hypothesis that is influenced by non-random events. 
The **p-value**, or probability value, tells us the likelihood that we would see similar results if we tested our data again, if the null hypothesis is true. Therefore, we use the p-value to provide quantitative evidence as to which of our hypothesis are true. 
When we compare our p-value of 5.25e-11 (seen in the image above) against a significance level of 0.05, we see that our p-value is much smaller than our significance level. Therefore, we can state that there is sufficient statistical evidence that our null hypothesis is NOT true, meaning our model shows that our dependent variable is effected by the non-random independent variables.

**3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**
This linear model predicts mpg of MechaCar prototypes fairly well. From our linear regression model (seen in the image above), the r-squared value is 0.71, which means that roughly 71% of the variability of our dependent variable (mpg) is explained using this linear model.
The lack of significant variables is evidence of overfitting. Overfitting means that the performance of a model performs well with the current dataset, but fails to generalize and predict future data correctly. 

