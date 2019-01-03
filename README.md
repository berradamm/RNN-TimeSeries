# RNN-TimeSeries
Predicting the behaviour of functions 


## Building the Neural network
When we deal with Time Series we need to prevent some problems such as vanishing gradient. Therefore we use a particular architecture. The LSTM is the most common but recently a new one has became the state of the art architecture ensuring good result and better performances, The GRU architechture

![image](https://user-images.githubusercontent.com/45148200/50423198-b051c480-0852-11e9-8940-1f8fd5c08542.png)

## The predicition 
Here we predicted the behaviour of the function sinus on a regular discretization. I also add the alternative of another prediction on an irregular time basis. 
Here are both result:
Regular Discreatization of sinus:

![image](https://user-images.githubusercontent.com/45148200/50423419-40910900-0855-11e9-914f-e0cf7833e131.png)

Irregular Discreatization of x:

![image](https://user-images.githubusercontent.com/45148200/50423413-31aa5680-0855-11e9-8771-5152c9ff1892.png)

