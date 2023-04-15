# OV2.5 Probability Calculator
In this project, I created a prediction model in Excel that calculates the probability of a soccer match ending with 3 or more goals, as well as the likelihood of it ending with 2 or more goals (known as OVER 1.5 goals). The OVER 1.5 market is often considered a safer bet when the OVER 2.5 market is less promising.

To build the model, I used data from the English Premier League from the 2015/2016 season onwards.

## Data Collection and Cleaning
To collect the data for this project, I downloaded eight Excel files from football-data.co.uk, one for each season. While each file contained soccer data from the top 25 European leagues, I only needed data from the English Premier League (EPL). To isolate the EPL data, I used VBA to split each Excel sheet.

Next, I used Power Query to combine the eight Excel files, which now only contained EPL data, into one file. I then transformed the data by eliminating unnecessary columns and resolving any inconsistencies.

By using VBA and Power Query to streamline the data collection and preprocessing process, I was able to save time and ensure the accuracy of the data used in the prediction model.

## The Analysis Process
The analysis for this project focused on four key areas: the league record, the home team record at home, the away team record while away, and the head-to-head record. To calculate the probability of the OVER 2.5 and OVER 1.5 markets, I considered the following factors:

1) The league's average goals per match
2) The percentage of games in the league that ended with at least 3 goals
3) The percentage of games in the league that ended with at least 2 goals
4) The offensive and defensive record of the home team when playing at home
5) The percentage of the home team's games that ended with at least 3 goals
6) The percentage of the home team's games that ended with at least 2 goals
7) The offensive and defensive record of the away team when playing away
8) The percentage of the away team's games that ended with at least 3 goals
9) The percentage of the away team's games that ended with at least 2 goals
10) The average goals per match in the head-to-head matches
11) The percentage of head-to-head games that ended with at least 3 goals
12) The percentage of head-to-head games that ended with at least 2 goals

By considering all of these factors, we were able to develop a comprehensive prediction model that takes into account various variables to calculate the probability of a soccer match ending with 2 or more goals (OVER 1.5) or 3 or more goals (OVER 2.5).

## Data Visualization
To calculate the probability of a soccer match ending with 2 or more goals (OVER 1.5) or 3 or more goals (OVER 2.5), we assigned a score to each of the factors listed above. We then converted the total score to a percentage, which served as the probability score. This score was displayed in two speedometer or gauge charts - one for the OVER 2.5 market and the other for the OVER 1.5 market.

The higher the probability score, the greater the likelihood of success. By presenting the results in this format, it is easier for users to interpret and understand the probability of each market.

To complete this project, I utilized a variety of skills and tools, including Power Query and Power Pivot, which allowed me to transform and manipulate the data effectively. I also employed DAX functions within Power Pivot to perform calculations and create the necessary metrics for analysis.

In addition, I utilized conditional formatting to highlight important information and create a visual representation of the data. I also employed VBA to split the Excel sheets containing data for all 25 European leagues into separate files for the English Premier League. Finally, I utilized advanced charts, such as speedometer or gauge charts, to display the results of the analysis in a clear and concise manner
