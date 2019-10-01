# Python-Basics

https://pandas.pydata.org/pandas-docs/stable/getting_started/10min.html

https://www.dataquest.io/blog/numpy-tutorial-python/?utm_source=mybridge&utm_medium=blog&utm_campaign=read_more

https://github.com/rougier/numpy-100/blob/master/100_Numpy_exercises.ipynb

https://stattrek.com/hypothesis-test/proportion.aspx?Tutorial=AP

https://medium.com/analytics-vidhya/balance-your-data-using-smote-98e4d79fcddb
(How to Deal with Imbalanced Data using SMOTE)

https://towardsdatascience.com/step-by-step-guide-to-creating-r-and-python-libraries-e81bbea87911
(Step-by-Step Guide to Creating R and Python Libraries (in JupyterLab))

Towards Data Science Articles:
(Graph Algorithms)
https://towardsdatascience.com/data-scientists-the-five-graph-algorithms-that-you-should-know-30f454fa5513

SEABORN: seaborn.pydata.org/tutorial/color_palettes.html

#Reading a file 

import csv
with open('winequality-red.csv', 'r') as f:
wines = list(csv.reader(f, delimiter=';'))
print(wines[:3])
