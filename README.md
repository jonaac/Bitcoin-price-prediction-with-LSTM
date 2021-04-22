# Bitcoin price prediction with Deep RL

In this project, I take a dataset of bitcoin prices, preprocess the data, and implement two LSTM models. The first model predicts bitcoin's day-to-day price and the second model predicts day-to-day price differences. Results showed that the first model'd predictions were able to follow the trend and direction of pricing correctly, however there is a considerable mismatch in the predicted values and the true values. The second model's predictions were more accurate.

## Libraries

```
Python
tensorflow
sklearn
matplotlib
pandas
numpy
```

## Results

To the left you can see the prediction of the day-to-day pricing of Bitcoin, to the right you can find the prediction of day-to-day price changes of Bitcoin.
<p align="center">
	<img width="250" src="https://jonaac.github.io/img/lstmprediction.png" />
	<img width="250" src="https://jonaac.github.io/img/lstmchangeprediction.png" />
</p>

## Further Work

This is an unfinished project, work that I would like to expand on:
1. Use a more extensive dataset
2. Compare both models in terms of which one is better for trading purposes, which one will return the highest profit
3. Define a criteria to buy, sell, or keep bitcoin based on the predictions made by the LSTM models.
4. Explore the idea of having a Reinforcement Learning agent who's action are Buy, Sell or Keep learn how to maximize profit based on the predictions.
