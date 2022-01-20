# Data Visualization
## Introduction
The data used below are [survey]( https://docs.google.com/forms/d/1YqZP3Ad6lMBzBrWGZy_z3YL35_obh1nmOuDgmhpYhWU/edit?usp=sharing) results. The survey was created as part of the course "IT-Organisation and Computer Service Management". 70 people were interviewed about their expectations from the banking service using the SERVQUAL service assessment method. In order to work with the table, it must be loaded on the home page in localhost.

A little about the data with which we will work. The essence of the method is to find out how important certain parameters are for users in each of the 5 categories (tangibles, reliability, responsiveness, assurance, empathy) on a 7-point scale (1 - not important at all, 7 - very important), and then compare the expectations for two groups of people (in my case, men and women. Unfortunately, I did not find representatives of other genders). We will build all kinds of graphs based on the results obtained during the survey.

We can represent this data in completely different ways. It is important to understand what exactly we want to know. Therefore, below are various ways to visualize the data obtained.

All data is recorded in an Excel spreadsheet. To read the table, we will use the xlrd library. (This is not the only library with which you can work with tables, but for me the most convenient).

## Bar Plots
Bar charts clearly show the difference between categories. In principle, depending on what information we want to compare, we can simply form groups in different ways and get the necessary information. Let's consider three types of column charts - regular, compound and grouped.

### Regular Bar Plots
The data presented is the average value for each of the 5 parameters in the group of interviewed women and men. According to these graphs, one can understand how important each of the parameters is within each surveyed group.

### Compound Bar Plots
The data presented is the average value for each of the 5 parameters in the group of interviewed women and men. The data is displayed as follows: the upper bound of one parameter is the lower bound of another. According to this graph, you can understand how important each of the parameters is for all respondents.

### Grouped Bar Plot
The data presented is the average value for each of the 5 parameters in the group of interviewed women and men. The corresponding parameters are displayed together (ie the average value for parameter 1 in the group of women and the average value of parameter 2 in the group of men). According to this graph, you can understand for which group each of the parameters is more significant and by how much. In other words, we can compare two groups within each of the parameters.

## Line Plots
Line plots are used when one variable is highly dependent on another. Line graphs show the covariance of two variables.

In our case, the use of line graphs can only make sense if we compare how important all 5 parameters are for each person from one of the two groups. Below are the graphs separately for women and for men; Using this method of data visualization, it is impossible to compare data obtained in different groups, because there are no covariances of variables

## Radial Chart
The radial chart is useful when we want to compare the parameters of the same entity. Here we will compare the average value of the importance of each of the parameters for two groups of people.

## Histograms
Histograms are useful for representing the distribution of data. Of course, this type of plot is most useful for the probability density distribution. However, we will use this type of graph to look at the distribution of the ages of the survey participants.
