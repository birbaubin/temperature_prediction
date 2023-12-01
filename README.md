# Temperature forecasting
 
The goal of this project is to predict the temperature of the next month based on the previous 24 months. The data is from the [NASA GISS Surface Temperature Analysis plateform](https://data.giss.nasa.gov/gistemp/).
This specific dataset is for the Carpiquet commune in France [Carpiquet weather data](https://data.giss.nasa.gov/cgi-bin/gistemp/stdata_show_v4.cgi?id=FRM00007027&ds=14&dt=1).
We try different models and compare them to see which one is the best for this specific problem.
The models we try are:
- Naive predictions (predicting the temperature of the next month to be the same as the current month, or the average of the last two months),
- Neural network,
- Convolutional neural network,
- LSTM
