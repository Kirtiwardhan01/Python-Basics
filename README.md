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

SEABORN: 
seaborn.pydata.org/tutorial/color_palettes.html
http://seaborn.pydata.org/tutorial/aesthetics.html

Python Counter() function:
https://medium.com/datadriveninvestor/an-introduction-to-python-counter-47948fdd9c1a

25 Useful Python Snippets to Help in Your Day-to-Day Work
https://medium.com/better-programming/25-useful-python-snippets-to-help-in-your-day-to-day-work-d59c636ec1b

Swifter packaage to make pandas apply faster
https://towardsdatascience.com/add-this-single-word-to-make-your-pandas-apply-faster-90ee2fffe9e8 

Introducing Bamboolib — a GUI for Pandas
https://towardsdatascience.com/introducing-bamboolib-a-gui-for-pandas-4f6c091089e3

#Reading a file 

import csv
with open('winequality-red.csv', 'r') as f:
wines = list(csv.reader(f, delimiter=';'))
print(wines[:3])
