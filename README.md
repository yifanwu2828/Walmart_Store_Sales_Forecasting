# Walmart_Store_Sales_Forecasting
This is a project base on kaggle's competition. The description is following:

One challenge of modeling retail data is the need to make decisions based on limited history. If Christmas comes but once a year, so does the chance to see how strategic decisions impacted the bottom line.

In this competition, job-seekers are provided with historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and participants must project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.

This competition is evaluated on the weighted mean absolute error (WMAE):

WMAE = 1/∑wi * sum(wi * abs(yi−y^i))

where
n is the number of rows
y^i is the predicted sales
yi is the actual sales
wi are weights. w = 5 if the week is a holiday week, 1 otherwise
