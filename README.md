
# Multiple-Linear-Regression

Multiple Linear Regression
In the last section, you saw how we can predict life expectancy using BMI. Here, BMI was the predictor, also known as an independent variable. A predictor is a variable you're looking at in order to make predictions about other variables, while the values you are trying to predict are known as dependent variables. In this case, life expectancy was the dependent variable.

Now, let’s say we get new data on each person’s heart rate as well. Can we create a prediction of life expectancy using both BMI and heart rate?

Absolutely! As we saw in the previous video, we can do that using multiple linear regression.

If the outcome you want to predict depends on more than one variable, you can make a more complicated model that takes this into account. As long as they're relevant to the situation, using more independent/predictor variables can help you get a better prediction.

When there's just one predictor, the linear regression model is a line, but as you add more predictor variables, you're adding more dimensions to the picture.

When you have one predictor variable, the equation of the line is

y = m x + by=mx+b


![just-a-simple-lin-reg](https://user-images.githubusercontent.com/25523756/115101042-e91b7900-9ef5-11eb-860b-3d1c09067c42.png)



Linear regression with one predictor variable

Adding a predictor variable to go to two predictor variables means that the predicting equation is:



To represent this graphically, we'll need a three-dimensional plot, with the linear regression model represented as a plane:


<img width="219" alt="Screen Shot 2021-04-16 at 8 55 51 PM" src="https://user-images.githubusercontent.com/25523756/115101081-30a20500-9ef6-11eb-8da4-f7ebdfd5a7f1.png">


![just-a-2d-reg](https://user-images.githubusercontent.com/25523756/115101116-7b238180-9ef6-11eb-906f-f1431baa029c.png)

<img width="780" alt="Screen Shot 2021-04-16 at 8 57 29 PM" src="https://user-images.githubusercontent.com/25523756/115101117-824a8f80-9ef6-11eb-8b98-9a0ca9493397.png">
<img width="797" alt="Screen Shot 2021-04-16 at 8 57 38 PM" src="https://user-images.githubusercontent.com/25523756/115101120-85de1680-9ef6-11eb-8e26-56225182bb98.png">




