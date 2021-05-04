# shopify-challenge-data-science
Data science shopify Challenge

## Question 1
1. Possibilities could be that the average was calculated wrongly, Simple mistakes can happen. Maybe we can split the average value weekly and see if the values are still odd.

2. Well, I ran a few queries as you can see [here](https://github.com/roykhoury/shopify-challenge-data-science/blob/main/shopify-datascience-challenge.ipynb) and I noticed that a *SINGLE* user_id, ordered 17 seperated orders, of 2000 items, having a total of 704000$ every order. This obviously will be accounted for.
So a solution would be to exclude any orders from this user_id. And recalculate the AOV.

3. The calculation excluding this user_id goes to: 754.09$, as seen [here](https://github.com/roykhoury/shopify-challenge-data-science/blob/main/shopify-datascience-challenge.ipynb)
