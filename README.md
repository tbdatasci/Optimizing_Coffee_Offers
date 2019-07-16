# Optimizing_Coffee_Offers
This is a Udacity project done on mock Starbucks data to find the most profitable offers to give each customer.
## Optimize Incremental Revenue
I decided to look at this project in terms of what offer(s) I can give to a customer to maximize Starbucks' incremental revenue from that person.  If a customer already buys every coffee they ever drink from Starbucks, then there may be no room to grow there, and a promotion to them may be useless.  So, I compared spending while under the influence of a promotion against spending while not under the influence of a promotion.
## Python libraries used
pandas as pd
numpy as np
math
json
% matplotlib inline
matplotlib.pyplot as plt
time

from sklearn.model_selection import GridSearchCV, StratifiedKFold, KFold, GroupShuffleSplit
from sklearn.ensemble import RandomForestRegressor, GradientBoostingRegressor
from sklearn.model_selection import train_test_split
from sklearn.pipeline import Pipeline, FeatureUnion
from sklearn.preprocessing import StandardScaler
from sklearn.metrics import mean_squared_error

