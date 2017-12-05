### ***Project 1 Feedback***

***Nico Van de Bovenkamp***

***

**Overall:** Good work on this first assignment! Your answers are definitely well worded, concise, and you are grasping most of the key concepts. There are a couple that I think you could use a bit of a refresher on. Check out this [correlation guide here](https://www.datascience.com/learn-data-science/fundamentals/introduction-to-correlation-python-data-science). As we go along, all of the key points on distributions, modeling, assumptions on data, and process will fall into place.


**Some Notes**

***Part 1***
* *Q.4* "this grad school" is a very good, subtle point that many people miss out on. Scope of your data is crucial. This may not generalize to all admissions processes.

***Part 2***
* *Q.1* As you can see below, we also want to find out about the distribution of the data, the relationships between variables, the quality of the data, outliers, and much, much more!
* *Q.2b* You could use a bubble and dot chart, but you could also use histograms and KDE's (a density graph that we discussed in class. It looks like that Violin plot, but right side up!).
* *Q.3a* Multicollinearity ([a great term to know!](https://onlinecourses.science.psu.edu/stat501/node/343)) doesn't quite get to outliers. Outliers are data points that are extreme, and may be some kind of error or anomaly. They may fundamentally skew your analysis and models by falsely indicating the underlying distribution is different. Thus, you want to test for them, and handle them in some intelligent way.
* *Q.3b* You can also use some statistical tests like a t-test!
* *Q.4a* It's not quite just similar variations, but also that they are linearly related. In fact, you could make a linear combination of them to model something! Like our ad sales example in class!

**Something to think about**

We touch on this a bit in class, but think about how you can apply statistical tests to your data. There are many handy tests to determine difference of means (very useful), tests to determine assumptions of an underlying distribution, etc. For example, there are specific tests which will estimate how close a given distribution is to a normal distribution.

Also, check out this KDNuggets post on [outlier analysis](https://www.kdnuggets.com/2017/02/removing-outliers-standard-deviation-python.html) in Python!
