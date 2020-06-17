# B2B Pricing Optimization
This is a group project. Team 4J includes Jing Li, Jacqueline Huang, Jiayin Liu, Jack Ye.


### Goal
This project aims to optimize contract discount for each company to maximize the expected total revenue.


### Analysis
- We first built several logistic regression models to predict the probability of contract win using historical data.

- Then we applied pricing optimization model for using each prediction model results to find the best-performing one.

- By comparing the evaluation metric (optimized revenue/ actual revenue ratio), we determined best-performing optimization model, which leads to 61.2% revenue increase in the hold-out sample.


### Result and Recommendation
By using the optimization model, the expected revenue/ actual revenue ratio achieved 1.612. 

Demands and willingness-to-pay of each product depend on the product properties and its position in the market. Also, new customers have different expectations and concerns from the existing customers. As a result, to satisfy different customers and generate the largest revenue, the company should segment the customers according to several characteristics such as
products they are interested in, if they are new customers, and even whether deals are made at the end of quarter. With customer segmentation, the company can set up different discount depths (discount/amount) for different segments.

