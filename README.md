# Gradient-Descent-with-Linear-Regression
Gradient Descent Implementation with Linear Regression implemented using Python with Housing Prices Dataset
# Gradient Descent 

Gradient Descent is an optimization algorithm
that works iteratively and aims to find the minimum value of a convex function with respect to a set of parameters.
This process is used in in many machine learning processes .

## Explanation

Let's take an example to understand Gradient Descent using a real life example

```
Let's move back to our school days ,
My friends and I always find to an argument that who is going to treat everyone in the canteen , To held this argument we often have a paper ball competition . 
In this paper ball competition we all were given set number of paper balls and our objective is to throw as many paper balls in dustbin as much as possible ,
person with the lowest score  that is person with least number of balls in the dustbin had to treat everyone that day , 
Now  suppose it's your turn and you are not sure with how much strength is required to throw the paper ball in the dustbin , so you random guessed to some degree ,
for example 30% of your strength will do and you make an attempt but you fail so you make a reattempt making some modifications in your strength so you estimate how short the ball fell short from the dustbin  so you readjust strength to make a successful throw , for example 60% now you again throw a paper ball but again failed . Now you make an third attempt with adjusted strength  for example 50% will work and BINGO you made it .

This is what we actually do in gradient descent 
```

## How Above Example is Analogy to Gradient Descent Algorithm

```python
In the above example , First we initialized our strength with 30% , This is Random Initialisation in Gradient Descent .

Then in second attempt we make an attempt with required strength , Similarly In Gradient Descent we Generate Predictions

Then we estimate how far the ball is from dustbin , Similarly in Gradient Descent we Calculate Cost/Error with respect to actual value 

Then we adjust our strength by updating it , Similarly we update parameters in Gradient Descent i.e. slope and intercept in Linear Regression Line . 

Then we again make a reattempt until we start scoring , similarly we start making accurate predictions iteratively until the cost function is minimum and hence we get the accurate results .

```

## Steps Involved in Gradient Descent
1. Random Initialisation
2. Generating Predictions
3. Calculating Cost
4. Updating Parameters


