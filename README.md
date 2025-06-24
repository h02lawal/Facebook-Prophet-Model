I used the Facebook Prophet model to build a predictive model, which tried to predict the number of passengers in an airline, 
this prediction can be used by a company to view expected sales.

I built another model that used the statsmodel passenger dataset to make predictions, this model took in extra regressors to give the model insights
into how other variables can affect the amount of passengers in an airline. The regressors were population and airline capacity, these were added because with
a population increase in an environment we can expect to see more purchases of various services one of which will be airplane tickets. If there's an increase in demand
for a service like flying then it can be assumed that airlines will also try to increase their capacity for passengers.

A good benefit of the Facebook Model is that it gives us the ability to see the effect of trend and seasonality on the data, it also allows us to remove each(trend or seasonality)
and see how our data behaves. In this program we can see that we have an upward trend and that there's a peak passenger count around July(seasonal data).

This is a very important tool that can be used to help companies forecast and make important plans based on the data they have. 
