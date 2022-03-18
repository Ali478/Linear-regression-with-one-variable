# Linear-regression-with-one-variable
In this part of this exercise, you will implement linear regression with one variable to predict proﬁts for a bakery franchise. Suppose you are the Chief Executive Officer of a bakery and are considering diﬀerent cities for opening a new outlet. The chain already has outlets in various cities and you have data for proﬁt and population from the cities. You would like to use this data to help you select which city to expand to next. 
The ﬁle ex1data1.txt contains the dataset for our linear regression problem. The ﬁrst column is the population of a city and the second column is the proﬁt of an outlet in that city. A negative value for proﬁt indicates a loss. 
# Plotting the Data 
Before starting on any task, it is often useful to understand the data by visualizing it. For this dataset, you can use a scatter plot to visualize the data, since it has only two properties to plot (proﬁt and population). (Many other problems that you will encounter in real life are multi-dimensional and can’t be plotted on a 2-d plot.) 
# The plot should look like Figure 1, with the same red “x” markers and axis labels.
![Screenshot from 2022-03-19 04-00-39](https://user-images.githubusercontent.com/54278016/159095088-db4c6575-7f0c-4c43-a26f-724e45636abd.png)

# Gradient Descent
In this part, you will ﬁt the linear regression parameters θ to our dataset using gradient descent.
# Update Equations
The objective of linear regression is to minimize the cost function
![Screenshot from 2022-03-19 04-02-52](https://user-images.githubusercontent.com/54278016/159095246-df37d8d8-1b56-4516-bb91-792d6f9b73e9.png)
# Implementation (COMPUTING cost and Gradient descent)
After you have implemented gradient descent algorithm and trained the model, the plot should look as
shown in Fig 2.
![Screenshot from 2022-03-19 04-04-16](https://user-images.githubusercontent.com/54278016/159095334-4f2b4c15-b8f4-4793-91d3-08026318e29b.png)
