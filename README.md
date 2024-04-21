
# Task 1 ~ TSF-GRIP
# The Sparks Foundation-Graduate Rotational Internship Program (TSF-GRIP)
## Date: February 2024
## Domain: Data Science & Business Analytics

### Task: Prediction using Supervised Machine Learning (Level - Beginner)

### Introduction

Hi everyone, welcome to today's video. In this session, we'll be diving into the world of predictive modeling using supervised machine-learning techniques. Specifically, we'll go through a problem: predicting a student's percentage based on the number of hours they study. This task is part of The Sparks Foundation Internship Program in the domain of Data Science & Business Analytics.

### Explaining the Task
To get started, let's understand the nature of our problem. We're dealing with a regression task, where we aim to predict a continuous value, in this case, the percentage score of a student. This differs from classification, where we predict discrete classes. In this case, we're dealing with a simple linear regression problem since we have two variables: the number of study hours and the percentage scores. The number of hours will be X (independent variable) and the expanded percentage will be Y which is also called the dependent variable.

### Implementing Linear Regression
Now, let's delve into the implementation. We'll be using Python's Scikit-Learn library to perform linear regression. This involves fitting a straight line to our data points to model the relationship between study hours and percentage scores.

### Importing Libraries:
First, we import the necessary libraries including pandas, numpy, and matplotlib for data manipulation and visualization.

### Loading and Displaying Data:
Next, we load our dataset from the provided URL and display the first few rows to get a glimpse of our data.
URL: http://bit.ly/w-data

### Exploratory Data Analysis:
We conduct exploratory data analysis by visualizing the distribution of study hours and percentage scores using histograms. Though histograms didn't reveal much, a scatter plot helps us identify a positive linear relationship between study hours and percentage scores.


### Preparing the Data:
Before training our model, we split the data into training and testing sets and reshaped them as required by Scikit-Learn.


### Training the Model:
Now, it's time to train our linear regression model using the training data.

### Visualizing the Regression Line:
Now let's plot the regression line on the scatter plot to visualize how our model fits the data. A regression line is a straight line that describes how a dependent variable Y changes as an independent variable X changes.

### Making Predictions:
Finally, we use our trained model to predict the percentage score for a given number of study hours, demonstrating the practical application of our regression model.

### Conclusion
And that's it! We've successfully implemented a linear regression model to predict student percentage scores based on study hours. I hope this video has been informative and helpful in understanding the fundamentals of supervised machine learning. Thank you for watching. If you have any questions or suggestions for future videos, feel free to leave them in the comments below. Don't forget to like and subscribe for more content. Until next time, happy coding!

#### YouTube Video & LinkedIn Post
[Youtube](https://youtu.be/hha0LB1xY9s)
[LinkedIn Post](https://www.linkedin.com/posts/m-omer713_datascience-machinelearning-tsfgrip-activity-7187423479531520000-KNuh?utm_source=share&utm_medium=member_desktop)
