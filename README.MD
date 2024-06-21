Iris - Logistic Regression 

Table of content:

1.Project files explanaition

2.Task description

3.Task purpose

4.The learning objectives


1. File - Iris.csv - This is the database the Logistic Regression is applied to. 
File Iris_Logistic_Regression.ypynb - code showing the process of the Logistic Regression application. 
File - Logistic_Regression_Optional - additional task using the same methods
This is in-depth EDA on the Titanic dataset provided including descriptions of the EDA and visualisations.

2. This task is a take on the supervised learning Logistic Regression model. The project is based on the Iris database.

3. Main Task Purpose:

● The dataset consists of three classes of irises. The objective is to create a
classifier that will predict whether an iris belongs to the ‘Iris-setosa' class
or not.
This means that we have two classes: ‘Iris-setosa' and not-‘Iris-setosa’
(which includes 'Iris-versicolour' and 'Iris-virginica').
○ Identify your independent variable x.

○ Encode your dependent variable y such that ‘Iris-setosa' is encoded
as 0, and 'Iris-versicolour' and 'Iris-virginica' are both encoded as

(0 corresponds to the 'Iris-setosa' class, and 1 corresponds to the
not-‘Iris-setosa' class.)

○ Split the data into a training and test set.

○ Use sklearn’s logistic regression function to fit a model and make
predictions on the test set.

○ Use sklearn to generate a confusion matrix, which compares the
predicted labels to the actual labels (gold labels).

○ Analyse the confusion matrix and provide a prediction, in a comment,
on whether the model is likely to have higher precision, higher recall,
or similar precision and recall.

○ Write your own code to calculate the accuracy, precision, and recall,
and check whether your prediction was right.

Additional Task Objective:

It is a repetition of the main task with a slight variation whereby we only have all three
categories ‘Iris-setosa', 'Iris-versicolour', and 'Iris-virginica'
corresponding to the numeric values 0, 1, and 2 respectively; this will now
be a three-class problem. Observation on how this changes the confusion matrix.

4. The learning objective is the practice in application of the Logistic Regression models and analysis of its effectiveness by using the confusion matrix and accuracy evaluations.
