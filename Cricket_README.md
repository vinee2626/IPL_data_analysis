# Sports analysis on IPL data set for GRIP - The Sparks Foundation Internship

This task consists of an exploratory data analysis over the cricket, IPL data set. Whereby, I have evaluated the best players, 
teams, venues- locations where the matches were played the most, most preffered toss decision, distribution of batting and bowling first
upon winning the toss, number of runs, number of bowls played by the teams, frequency of 4s and 6s hit by players.

The libraries in this project include pandas, matplotlib, seaborn to compute and visualize the data to answer certain 
questions in order to gain meaningfull insight from the data.

After creating a dataFrame and reading the file from my csv files, I started this with data wrangling and reduced the noise by checking for any null, NaN data in my dataFrame and also getting rid of any unwanted values. 

# To make the most out of data and understand it in a better way, I have answered the questions as follows as a part of data analysis:

 1. Which season had the most number of matches?
 2. Which city and venue accomodated the most number of matches untill now?
 3. Which team is the strongest ?
 4. What does the toss result accomodate for the most? Fielding and batting ?
 5. Which player should be endorsed for an advertisement ? 
 6. Distribution of winners according to bowl or bat 
 7. Winners of each season  
 8. What does the teams prefer the most? Bat or Bowl first?
 9. The number of times the toss winning time won the match ?
 10. Number of bowls played by each team 
 11. Top 5 batsman of IPL
 12. Which player has lasted through a whole match and made 200 runs in IPL?
 13. Which players have hit a 6 throughout IPL the most?
 14. Which players hit a 4 the most throughout the IPL tournament?
 15. Which pair of batsman is the most famous ?

# To perform this analysis I went through several procedures as mentioned below:

 - Reading data from csv file and create a new DataFrame.
 - Created new dataframes when required and made changes to columns.
 - Used groupby function to perform aggregate function on this data.
 - Used certain modules of matplotlib and seaborn to visualize the data in the form of customized bar charts and line charts.
 - Used seaborn to define correlation using heatmap with annotations.
 - Labelled those graphs.
 - Renamed the column names.
 - Used loc function and sort_values.
