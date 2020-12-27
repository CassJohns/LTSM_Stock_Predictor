# LTSM_Stock_Predictor

## EVALUATE THE PERFORMANCE OF EACH MODEL ##


*Which model has a lower loss?*

The closing price model had a lower loss of .0035 compared to the fear and greed model which had a loss value .0714 using the same parameters.


*Which model tracks the actual values better over time?*

The closing price model follows the actual values better over time.  The FNG model really didin't predict the same amount of movement and variance compared to the real data.  


*Which window size works best for the model?*

A smaller window size works best for both models.  The closing price model actually performed the best using the smallest window of 1; howevever this didn't optimize the FNG model.  A lower number around 3 is ideal for both models if trying to compare the two. 
