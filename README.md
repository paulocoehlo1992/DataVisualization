# DataVisualization with Dimple.js

##Introduction

This project is part Udacity Data Analyst nanodegree.From the variety of datasets provided by the udacity , i chose to create a visualization about famous Titanic-Survival dataset which is available on kaggle.I chose to go with dimple.js as it provided higher level abstraction to create visualizations quickly with a few lines of code.

##Summary

the visualization depicted the survival rate  of passengers in titanic-crisis based on passenger class and gender.

##Design
I created new dataset from the titanic dataset by using pandas having features like survival rate, class etc.I used dimple.js to create this visualization. I tired variety of charts including line chart, scatterplot etc but none of them sufficiently represented the comparision aspect of the data being visually encoded. Bar chart in this case does the job  of capturing 
different aspects of data being encoded, fairly well.

##Feedback

###feedback 1:
" the chart does not capture the comparison aspect of data across classes. Scatterplots are not good for comparisions as they are are to used to determine trends in bivariate analysis. You should try using bar chart or something else"

###Feddback 2:
"Try different visual encoding for gender variable. It would become easy to distinguish between them ."

###Feddback 3:
"You could improve this chart by adding legends. This could make it super easy to see which color represented what in the chart. Try to add legends. Overall, Bar chart is doing a great job so far"

##Resources

1.Official dimple.js documentation "http://dimplejs.org/"
2.Bar Graph example "http://dimplejs.org/examples_viewer.html?id=bars_vertical_grouped"
3.pandas
4.Data visualization with D3.js
