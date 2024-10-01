# Market-Index-Prediction-using-Machine-Learning

Libarires used are
Numpy
Pandas
Keras
Model used
I have used LSTM model using keras library. It has 6 layers out of which 2 are Dropout layers to address overfetting and at total it has 50,851 paramteres. I have used 'adam' optimizer and mean squared error loss

Pre-processing
I have removed NA values using linear interpolation and normalised the data and reformated the data such that each input of model has shape (1,50,1). Means it has 50 input features which are clossing price of last 50 days.
