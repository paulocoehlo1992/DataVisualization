# DataVisualization with Dimple.js

##Introduction

This project is part Udacity Data Analyst nanodegree.From the variety of datasets provided by the udacity , i chose to create a visualization about famous Titanic-Survival dataset which is available on kaggle.I chose to go with dimple.js as it provided higher level abstraction to create visualizations quickly with a few lines of code.

##Summary

the visualization depicted the survival ratio  of passengers in titanic-crisis based on passenger class and gender.The percentage survival can be coputed by multiplying the proportion value to 100.the Survival ratio is defined as :

  ###survival ratio= (number of people survived ) / (number of people survived + number of people did not survive)

##Design
I created new dataset from the titanic dataset by using pandas having features like survival rate, class etc.In the created dataset"survival_by_class.csv" ,the column named "Survival rate " represents the proportion of people who survived out of total people travelling in that class across gender. For example ,the proportion of 0.42 , represents the ratio of female passengers who survived in class 1, to the total number of female passengers travelling in passenger class 1. I used dimple.js to create this visualization. I tired variety of charts including line chart, scatterplot etc but none of them sufficiently represented the comparision aspect of the data being visually encoded. Bar chart in this case does the job  of capturing different aspects of data being encoded, fairly well.

##Important Findings 

1.We can clearly see that survival ratio for female passengers are highest in passenger class 1, which was about 0.43 . Same goes with male passengers, survival ratio is highest in passenger class 1.This corroborate the fact that there was some bias in the titanic rescue mission towards class 1 passengers and females. 

2.We can also see that across all the passenger class, female have higher survival ratio as compared to male.

3.It is also interesting to note that male passengers in class 3, have slightly better survival ratio as compared to class 2. 

##Feedback

###feedback 1:
" the chart does not capture the comparison aspect of data across classes. Scatterplots are not good for comparisions as they are are to used to determine trends in bivariate analysis. You should try using bar chart or something else"

###Feedback 2:
"Try different visual encoding for gender variable. It would become easy to distinguish between them ."

###Feedback 3:
"You could improve this chart by adding legends. This could make it super easy to see which color represented what in the chart. Try to add legends. Overall, Bar chart is doing a great job so far"

##Resources

1.Official dimple.js documentation "http://dimplejs.org/"
2.Bar Graph example "http://dimplejs.org/examples_viewer.html?id=bars_vertical_grouped"
3.pandas
4.Data visualization with D3.js
