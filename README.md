# Stock Market Prediction

## Dataset
- Remote access : [Tiingo](https://www.tiingo.com/) [API](https://api.tiingo.com/documentation/general/overview) is used to get data of the stocks of previous 5 years, with symbol as AAPL for Apple and GOOG/GOOGL for Google class C/A. To get started with data we need a unique API key(provided to every user).

## Roadmap

- First we load the dataset using Tingo API and analyse it.

- After loading, we preprocess the data by use of MinMaxScaler and split the data into testing set and training set.

- Afterwards we convert array of values into a dataset matrix.

- Now we take first 100(1-100) values to predict 101st value and next 100(2-101) to get 102nd value and so on.

- After preprocess, we create Sequential model and then train it.

- After training, we use our model to predict and then inverse transform the data to get original value.

- Then we check the performance of our model by MSE.

- Following, we plot our graph of predicted values of test and train data.

- At last, we plot the predicted stock price for next 30 days.

## Documentation

- [Tiingo API](https://api.tiingo.com/documentation/general/overview)

- [MinMaxScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html)

- [Sequential model](https://keras.io/guides/sequential_model/)

- [Mean Squared Error](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.mean_squared_error.html)

- [Pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)

## Acknowledgements

 - [Krish Naik](https://www.youtube.com/watch?v=H6du_pfuznE&t=173s)

## Feedback

If you have any feedback, please reach out to me at puranshu@iitg.ac.in.

## License

[MIT](https://choosealicense.com/licenses/mit/)
