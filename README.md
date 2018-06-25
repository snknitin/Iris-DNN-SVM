# Iris-DNN-SVM

There are four notebooks in this repository in the Irist-DNN-SVM folder

1. Exercise 1 involves modifying the code to return a JSon type dictionary with information about the model and the predictions

        I tried different combinations for DNN classifier but they gave bad results. So i picked the one which gave better results - Hidden layer dimension = [10,30,10] and 5000 iterations.  

        SVM classifier was modified to apply 4 different kernels and store that result in a json   

        I additionally implemented a Decision Tree classifier since th description for the ffinal merge mentioned it.  
        The final classifier method combines all the results into one json dictionary for all three methods

2a. Contains the building bloccks and the concepts behind the LSTM with teh input, forget and output gates  
2b. Contains a time series data generator class to make it simple to plot and see the effect of the LSTM training to predict the next steps  
2c. Reinforcement Learning problem - I attempted it but my environment isn't configured properly so i left this unfinished for now.



