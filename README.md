# matplotlib-challenge
# Rebecca Watson 

#### Project Background: 
You've just  joined Pymaceuticals Inc., a new pharmaceutical company that specializes in anti-cancer pharmaceuticals. Recently, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated with a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.
The executive team has tasked you with generating all of the tables and figures needed for the technical report of the study. They have also asked for a top-level summary of the study results.

My tasks were to do the following:
- Prepare the data
- Generate summary statistics
- Create bar charts and pie charts
- Calculate quartiles, find outliers, and create a box plot
- Create a line plot and a scatter plot
- Calculate correlation and regression
- Submit your final analysis

#### Findings 
Being someone who loves research and science, this assignment was very helpful in helping me learn more about how data applies to my field. Sorting the data in this assignment was difficult at first. I knew what I wanted the end result to look like, but didn't realize how many steps needed to take place to get there. Through these steps, I found there was a better way to sort it than I originally had planned; randomly deleting data from a dataframe, is not the best way to go. 

When looking at the summary statistics, I noticed that there are two drugs which have a significant lower mean tumor volume. These two also have the lowest standard deviation and variance which could be significant in making a statement about the drugs' effectiveness. 

By looking at different charts of plotted data, it is easier to quickly identify if there is any bias in the dataset. The given set of data seems to have low bias when it comes to both gender and the number of mice tested with each drug. With these potential biases being about even across the board, it is fair to assume these are not factors in the results of our data. 

One last plot of significance is the scatter plot of weight versus average tumror volume. By looking at the chart of the drug "Capomulin", it is noted that as the weight of a mouse is higher, the average tumor volume is larger. This is confirmed by calculating the linear regression. 
