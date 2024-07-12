# predict rate-induced tipping 

## generate time series data with R-tipping and without R-tipping, in matlab programming
### Saddle-node system as an example
#### function for implementing the stochastic dynamical equation: "generate_tipts.m"
#### generate and plot the time series for demonstration: "Ensemble_simulations_Saddle_Node_System.m"
##### outputs: "time_series.jpg"

## demonstrate traditional EWS for predicting tipping: Critical Slowing Down (CSD), i.e., lag-1 autocorrelation and variance, in matlab programming
#### function for calculating CSD: "tpind.m"
#### generate and plot the time series of CSD for demonstration: "calculating_critical_slowing_down_indicators.m"
##### outputs: "CSD_indicators.jpg"

## deep learning for predicting R-tipping, in python progaramming
### jupyter notebook for training the neural networks, and saving trained model and loss values: "DLmodel_for_Saddle_Node_System.ipynb"
#### outputs: "best_model.pt", "losstrain.txt", "lossval.txt", "losstest.txt", "acctrain.txt", "accval.txt", "acctest.txt"
### libarary for implementing layer-wise relevance propagation (LRP) algorithm
#### folder "lrp", which is adaped from the existing github project: https://github.com/fhvilshoj/TorchLRP
### jupyter notebook for calculating R-tipping probability and LRP score: "DLmodel_for_Saddle_Node_System.ipynb"
#### outputs: "probabilityandlrpscore.mat"
