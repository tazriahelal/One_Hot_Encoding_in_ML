# One_Hot_Encoding_in_ML
One Hot Encoding in ML

Dummy Variables & One Hot Encoding in ML📝
Dummy Variables
A dummy variable (aka, an indicator variable) is a numeric variable that represents categorical data, such as gender, race, political affiliation, etc.

Technically, dummy variables are dichotomous, quantitative variables. Their range of values is small; they can take on only two quantitative values. As a practical matter, regression results are easiest to interpret when dummy variables are limited to two specific values, 1 or 0. Typically, 1 represents the presence of a qualitative attribute, and 0 represents the absence.
Dummy variables are another way in which the flexibility of regression can be demonstrated. By incorporating dummy variables with a variety of functional forms, linear regression allows for sophisticated modeling of data.

Want to know more on this topic in a descriptive way with example - Click this notebook
📌Dummy Variables & One Hot Encoding in ML📌
One Hot Encoding
One hot encoding is a technique used to represent categorical variables as numerical values in a machine learning model. The advantages of using one hot encoding include:

It allows the use of categorical variables in models that require numerical input.
It can improve model performance by providing more information to the model about the categorical variable.
It can help to avoid the problem of ordinality, which can occur when a categorical variable has a natural ordering (e.g. “small”, “medium”, “large”).
it works very well unless your categorical variable takes on a large number of values (i.e. you generally won't it for variables taking more than 15 different values. It'd be a poor choice in some cases with fewer values, though that varies.)

One hot encoding creates new (binary) columns, indicating the presence of each possible value from the original data. Let's work through an example.

![](https://www.googleapis.com/download/storage/v1/b/kaggle-forum-message-attachments/o/inbox%2F9494541%2F6854dbc9246c5bce007cb44d1ad57f2d%2Fonhotpic.PNG?generation=1681147435145406&alt=media)

The values in the original data are Red, Yellow and Green. We create a separate column for each possible value. Wherever the original value was Red, we put a 1 in the Red column.

Want to know more on this topic in a descriptive way with example - Click this notebook
# [📌Dummy Variables & One Hot Encoding in ML📌](https://www.kaggle.com/tazriahelal/dummy-variables-one-hot-encoding-in-ml)
Ref:

https://www.formpl.us/blog/nominal-ordinal-data

https://www.geeksforgeeks.org/ml-dummy-variable-trap-in-regression-models/

https://www.educative.io/blog/one-hot-encoding

https://www.youtube.com/watch?v=9yl6-HEY7_s&list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw&index=8

https://scikit-learn.org/stable/
