# [CrunchDAO Tournament](https://www.crunchdao.com/)

## Aim
- Build Predictive Models for different anonymized financial datasets 
- Develop understanding of Machine Learning (ML) Models related to Time-Series data
- Learn about Quantitative Finance
</br></br>

## Methods
- ML Models under exploration, From Scikit-learn
    - Random Forest Regressor
    - Extra Trees Regressor
    - XG Boost Regressor
</br></br>

- Information to review :
    - Time Series Analysis [MachineLearningPlus, ](https://www.machinelearningplus.com/time-series/time-series-analysis-python/)
    - DataCamp Community ( *if neccessary* )
</br></br>

- ML Models to explore :
    - ARIMA - [GFG Blog](https://www.geeksforgeeks.org/python-arima-model-for-time-series-forecasting/)
    - Deep Probabilistic Koopman - [Discord Community Resource](https://arxiv.org/abs/2106.06033), Sustainable amongst Energy-demanding ML Algorithms
    - N-beats - [Discord Community Resource](https://github.com/philipperemy/n-beats)
</br></br>

##  Takeaways
#### **API_KEY safe storage and retrieval**
- Storing API_KEY in a secret environment (*.env*) is neccessary to prevent security risks to the user account
- Reading API_KEY from *.env* is neccessary to push results through API
- *python-dotenv*, a consolidated library to access *.env* variables
- This [blog post](https://medium.com/@eyakubsorkar/reading-variables-from-env-file-on-python-cac5af8cefa2#:~:text=Reading%20variables%20from%20.env%20file%20on%20Python%201,the%20file%20where%20you%20import%2Fload%20yours%20.env%20) lays it all-out clearly
</br></br>

#### **ARIMA Model**
Source : [machinelearningmastery](https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/)
- **Auto Regression** : 
    - relationship model using dependency between raw observation and lagged observations
    - *p* , number of lag observations a.k.a lag order
- **Moving Average** : 
    - relationship model using dependency between raw observation and residual error from moving average model applied to lagged observations
    - *q* , size of moving average window a.k.a order of moving average
- **Integration** : 
    - differencing raw observations (n, n-1) to make time series stationary
    - *d* , a.k.a degree of differencing
- Used for forecasting Time Series which is non-linear (non-seasonal) and has patterns other than random white noise
