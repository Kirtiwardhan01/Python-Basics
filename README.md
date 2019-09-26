# Python-Basics

https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html

https://www.dataquest.io/blog/numpy-tutorial-python/?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more

https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises.ipynb

https://stattrek.com/hypothesis-test/proportion.aspx?Tutorial=AP

https://medium.com/analytics-vidhya/balance-your-data-using-smote-98e4d79fcddb
(How to Deal with Imbalanced Data using SMOTE)

#Reading a file 

import csv
with open('winequality-red.csv', 'r') as f:
wines = list(csv.reader(f, delimiter=';'))
print(wines[:3])
