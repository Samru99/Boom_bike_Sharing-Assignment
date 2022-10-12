# ** Boom Bike share
> 
----
### A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. So we have to help the company find what are the factors that can affect the business and they need to work on those to boost the bike sharing business on these predicted factors 
---
###  Business Goal: 
    Required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
----
# General Information
- The project is about how to analyze the data and giving the prediction for the bike sharing andd explaining what all variables affect the business and how much of an imapact they have on the target of the business
# All the process done in the assignment are:
1) Load & Read and understand the data 

2) Cleaning the data 

3)EDA

4)Visualizing the data 

5)Data preparation

6)Model Building

7)Splitting the data into Train and test data set 

8)Rescaling the features 

9)Buliding Linear and stats model 

10)Residual analysis on the Train data 

11)Prediction and Evaluation on TEST Data set

12)Calculation of R- square on test data 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
---

# Technologies Used

---
- This code imports the Pandas and nmpy library
```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt


import statsmodels
import statsmodels.api as sm
import sklearn
from sklearn.linear_model import LinearRegression
from sklearn.preprocessing import MinMaxScaler
from sklearn.model_selection import train_test_split
from sklearn.feature_selection import RFE
from sklearn.metrics import r2_score

import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor

```
We have used 
Pandas,
Numpy,
Seasborn,
Matplotlib,
Scikit learn,
SatsModel .
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


# Conclusion: 
Demand of bikes depend on year, holiday, temp, windspeed factors 
<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->