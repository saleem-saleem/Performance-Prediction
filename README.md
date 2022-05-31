Introduction
In this small project I implement a simple algorithmic model that predicts the score of an individual students at he end of the year. "G3" or the final grade will be our label (output) and the rest of the columns will be our features (inputs). First, I will explore the data to see if we can get a grasp of what is the story behind the data. I'm not looking for to just implementing a linear regression or random forest regression algorithm just to get the score. My aim is to understand what the data is telling us through visualizations (plotly, matplotlib, seaborn).

Outline of the Project
1) Extract the Data and Gather General Information of the Dataset
2) Visualize the three outputs ["G1", "G2" and "G3]
a) We will see how the data is distributed.
b) Gain some insights about the three grades. (Distribution Plots)
c) We will finally use "G3" as our output for our linear regression algorithm since it is the final and most important grade.
3) Data Structuring:
a) Drop the G1 and G2 columns.
b) Transform some of the columns into binary columns for future analysis.
c) Split the data (Training and Testing sets.)
d) Implement StartiefiedShuffleSplit to the two most important features in terms of correlation with G3.
e) Create a binary column and a criteria determining what score is a Failing and what score is a Passing Grade.
4) Data Analysis and Visualization
a) Students that passed and failed the course (Using Plotly) (%).
b) How did students perform by gender (Using Plotly). (%)
c) Correlation Analysis.
d) Number of Absences throughout the Course (Using Plotly)
e) Further Analysis.
5) Data Cleaning (Preparing the Data for our Algorithm)
a) Split the data into Numeric and Categorical Values.
b) Scale the Numeric and Categorical columns using StandardScaler in order to fit the data into our algorithms.
c) Select the best algorithm (Better score and accuracy) Make sure its not overfitting!
d) Select the best hyperparameters by using GridSearchCV
6) Conclusion: In this project, a deep analysis is done  of what could be possible factor on whether a student is likely to get a high score or a low score.The data does not contain that much information but still we were able to predict a pretty precise RandomForest Regressor algorithm that predicts what score a student will get in the foreseen feature by analyzing the features.
