# Optimizing_Coffee_Offers
This is a Udacity project done on simulated Starbucks data to find the most profitable offers to give each customer.
## Optimize Incremental Revenue
I decided to look at this project in terms of what offer(s) I can give to a customer to maximize Starbucks' incremental revenue from that person.  If a customer already buys every coffee they ever drink from Starbucks, then there may be no room to grow there, and a promotion to them may be useless.  So, I compared spending while under the influence of a promotion against spending while not under the influence of a promotion.
## Python libraries used
pandas as pd
<br>
numpy as np
<br>
math
<br>
json
<br>
% matplotlib inline
<br>
matplotlib.pyplot as plt
<br>
time
<br>
from sklearn.model_selection import GridSearchCV, StratifiedKFold, KFold, GroupShuffleSplit
<br>
from sklearn.ensemble import RandomForestRegressor, GradientBoostingRegressor
<br>
from sklearn.model_selection import train_test_split
<br>
from sklearn.pipeline import Pipeline, FeatureUnion
<br>
from sklearn.preprocessing import StandardScaler
<br>
from sklearn.metrics import mean_squared_error

