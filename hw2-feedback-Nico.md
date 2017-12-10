### ***Project 2 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this assignment! You are gaining a much better grasp of these concepts, and you are clearly getting more comfortable with Python. As we move forward try and take fuller advantage of Python by writing your own functions and playing with more of the methods that Pandas and Numpy have to offer. Also, let me know if you have any questions on modeling, as this is the next **big** section in our journey!


**Some Notes**

* *Q.9:* Typically when we refer to skew, we are referring to outliers. Thus, you are right, they distributions are approximately normal, but they have some values that are a bit lower than the rest of the distribution -- they are skewed left/down.
* Regarding co-linearity, there really ins't any hard-set rule... In general though, something like `r>0.5` would indicate some level of co-linearity. Most often, you will make note of this then continue in your analysis. As we had done in class, you will find that adding or dropping certain features will result in different levels of significance for predicting an outcome. So, if you notice that GRE is insignificant, but GPA is significant, then maybe GRE is in fact highly correlated with GPA and it wouldn't help you. In this case, correlation is low, so you will have some information encoded in GPA that you wouldn't in GPA.
* Regarding your analysis plan, fair enough! You could follow this method. We haven't gotten into modeling yet, but as we have done in class, you would just throw all of these values into the model! As in, you would be performing a, say, logistic regression from admission to your Prestige, GPA, and GRE. It will be more clear as we go along. Additionally, in your analysis plan you would also want to include how you plan to analyze and pre-process your data -- dropping outliers, imputing values, data transforms, etc.

**Something to think about**  
Dropping missing values can be necessary at times. In cases where you you have a lot of missing values, you might have to just drop those rows *or* ignore that feature all together (forget that column, we can't use it). However, as we proceed, you will find that data is gold to these algorithms. Very often, the more data you have, the more information you are giving to your model so it can generalize even better. To ensure we retain as much data as we can, a common practice is to fill missing values with the mean or median or mode so that you can keep those instances, without disturbing your distribution too much. Check out these guides:
https://machinelearningmastery.com/handle-missing-data-python/
https://chrisalbon.com/python/pandas_missing_data.html
