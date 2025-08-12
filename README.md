# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12-08-2025

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:
```
NAME : JAGANNIVASH U M
REG NO: 212224240059
```
```py
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error, mean_absolute_error, r2_score
from sklearn.preprocessing import StandardScaler
data=pd.read_csv("C:\\Users\\admin\\Downloads\\archive (7).zip")
plt.figure(figsize=(10,10))
sns.histplot(data['Price'], kde=True, color='green', bins=47)
plt.title("Distribution of House Prices", fontsize=14, weight='bold')
plt.show()
```










# OUTPUT:
<img width="918" height="823" alt="Screenshot 2025-08-12 142748" src="https://github.com/user-attachments/assets/0caf2d95-3ce6-4d92-b189-113ffec81b50" />







# RESULT:
Thus we have created the python code for plotting the time series of given data.
