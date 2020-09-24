# RNN_models
Contains two RNN autoencoder implementations and one RNN regressor implementation using PyTorch. This repository also contains a rnn_utils file containing useful functions such as hidden state repackaging and initialization. All the models support GRU and LSTM cells.

## rnn_ae
Contains two RNN autoencoder implementations : 
- RNN_ae is a vanilla RNN autoencoder that can also perform time series prediction. 
- DoubleRNNAE is a model specialized in reconstructing long multivariate time series (works well with around 200 points), focusing on the first and last time steps.

## rnn_reg
Contains one implementation of RNN regressor. This model performs regression between two multivariate series of same length. This type of regression is convenient when dealing with multi-sensor data for example.
