### Custom loss Functions

Suppose you want to train a function - But your training set is a bit noisy. What will you do ? You will start cleaning up your dataset by removing outliers. However, what if that turns our inefficient? Which loss function will you use to train the model? 

**Mean Squared Error** (MSE) might penalize the errors in your dataset and might train the model to be imprecise. 

**Mean Absolute Error** (MAE) might train the model however it might take longer to converge. And the trained model might not be precise. 

**Huber Loss**: [Huber loss](https://en.wikipedia.org/wiki/Huber_loss) is less sensitive to outliers in data than the squared error loss. It’s also differentiable at 0. It’s basically absolute error, which becomes  quadratic when error is small. 

