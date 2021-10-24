---
title: StatQuest Biostatistics - Introduction to Machine Learning (ML)
subtitle: 

# Summary for listings and search engines
summary: StatQuest course about Machine Learning (ML)

# Link this post with a project
projects: []

# Date published
date: 2020-03-29T00:00:00Z

# Date updated
lastmod: 2020-03-31T00:00:00Z

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: ""
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

categories:
- Machine Learning
- StatQuest

---

### Machine Learning (ML)

Machine learning is the scientific research of algorithms and statistical models for computer systems to perform specific tasks. It does not use explicit instructions, but instead relies on patterns and reasoning to complete tasks.  
Machine learning is considered a subset of artificial intelligence, and unsupervised exploratory data analysis in machine learning is also called data mining.

[Wikipedia Definition](https://en.wikipedia.org/wiki/Machine_learning):
Machine learning (ML) is the study of computer algorithms that can improve automatically through experience and by the use of data. It is seen as a part of artificial intelligence. Machine learning algorithms build a model based on sample data, known as "training data", in order to make predictions or decisions without being explicitly programmed to do so. Machine learning algorithms are used in a wide variety of applications, such as in medicine, email filtering, speech recognition, and computer vision, where it is difficult or unfeasible to develop conventional algorithms to perform the needed tasks.

  
There are two uses of machine learning: classification and prediction. The “prediction” here is easy to cause misunderstandings, because the job of machine learning is to make predictions (classification is also making predictions). Here, "prediction" corresponds to classification, and the two can be considered as predicting continuous variables and categorical variables respectively. In other words, classification is to predict the classification of categorical variables (whether spam, whether to buy), and "prediction" is to predict the specific value of a continuous variable (height, weight, etc.).

  
### Examples of predictive and categorical machine learning

The statistical models used in machine learning include Artificial neural networks, Decision trees, Support vector machines, Regression analysis, Bayesian networks, and Genetic algorithms.

Decision tree is a typical classification machine learning algorithm, the following is the style of a decision tree: it is a tree structure, the root node and the middle node are the questions, the left branch represents the answer is "yes", the right branch represents the answer is "no". The end node is the result of the decision tree: like StatQuest, dislike StatQuest :(. That is to say, this decision tree is to predict whether a person likes StatQuest.

{{< figure src="1.jpg" title="" >}}

If the following information is obtained for three people, then for the first person, like Silly Songs, then enter the left branch, dislike Machine Learning, then enter the right branch, like Statistics, and enter the left branch, so it is predicted that this person likes StatQuest.

The prediction results of the second person and the third person also like StatQuest, where the third person only needs to ask Machine Learning to get the classification result.

{{< figure src="2.jpg" title="" >}}


Linear regression is a classic predictive machine learning algorithm (regression can also solve the problem that the response variable is a categorical variable: such as Logistics regression). As shown in the figure below, the linear prediction result between Speed and Yam consumption can be obtained, and based on this, the speed of a person when his Yam consumption is 2.3.

{{< figure src="3.jpg" title="" >}}


### A key machine learning problem - bias variance tradeoff

For a machine learning model, the original data can be divided into at least two types: **training data** is used to build the model and **test data** is used to evaluate the pros and cons of the model.

Still taking the above linear regression as an example, as shown in the figure below, the red points are the original data for modeling, the blue points are the test data, the black line is the linear regression line, and the green line is a newly fitted regression line.

The result shows that the fitting result of the green regression line is much better than the black linear regression, because its fitting degree is 100%. But if you use the test data to measure the prediction effect of the two at this time, you can find that the deviation of the predicted value is greater than the deviation of the linear regression.

In other words, it does not necessarily mean that the model has a high degree of fit to have excellent predictive ability.

{{< figure src="4.jpg" title="" >}}

The deviation measures the degree of deviation between the expected prediction of the learning algorithm and the true result, and it describes the fitting ability of the algorithm itself. The worse the fitting, the greater the deviation.

Variance measures the changes in learning performance caused by changes in the training set of the same size, and describes the impact of data disturbance. The worse the model is perturbed by data, the greater the variance (the worse the predictive ability).

Although the deviation of the black regression line is greater than that of the green regression line, its predictive ability is better. Although the variance is not calculated, it can be predicted that the variance is relatively low. (The bias and variance in the bias variance tradeoff are different from the conventional bias and variance, pay attention to distinguish.)

### Why is there a change in the training set?

In actual machine learning, there are many models available, such as K-nearest neighbor algorithm and support vector machine. Which model to choose can be solved by cross-validation, that is, calculate and test all available models once, and use whichever model is excellent.

In this process, there is a problem that which part is used as training data and which part is used as testing data. In actual operation, all the data is split (for example, the data is divided into 4 parts, and the testing data is 1, 2, 3, 4 copies respectively, and the rest is training data, there are 4 data splitting schemes). Repeating the process again and again, so there will be changes in the training data.


More details please refer to [StatQuest course](https://statquest.org/video-index/). 

  
### Reference

1.	_Mitchell, Tom (1997). Machine Learning. New York: McGraw Hill. ISBN 0-07-042807-7. OCLC 36417892._
2.	_Hu, J.; Niu, H.; Carrasco, J.; Lennox, B.; Arvin, F., "Voronoi-Based Multi-Robot Autonomous Exploration in Unknown Environments via Deep Reinforcement Learning" IEEE Transactions on Vehicular Technology, 2020._
3.	_Bishop, C. M. (2006), Pattern Recognition and Machine Learning, Springer, ISBN 978-0-387-31073-2_

