*Instructions to run the code:
-After importing the dataset, process it to have a datetime index then proceed with the rest of the code provided in the github page.
-In case the frequency of the data is not daily, you can change it to weekly or yearly depending on the frequency,
make sure the frequency is noted in the datetime and the models.


*List of dependencies:
-numpy
-matplotlib.pyplot
-sklearn
-datetime
-statsmodel.api (for seasonal decompose)
-statsmodel.tsa (to import both ARIMA and Exponential Smoothing models) 
-pmdarima (for testing different ARIMA models)
-math (use of simple functions)
-tensorflow (used for the LSTM model, works directly in google colab but needs installation via the terminal in jupyternotebook)
-neuralprophet


*Instructions to download the dataset:
-Visit:
https://www.kaggle.com/datasets/dronio/SolarEnergy

*The LSTM model code is credited to Jason Brownlee. Reference link:
https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/