## Microsoft Movie Analysis
•	Student name: **Sheilah Sayo Machaha**
•	Student pace: **Part time**
•	Scheduled project review date/time: **Submission date due 16/04/2023*8
•	Instructor name: **Noah Kandie**
•	Blog post URL:https://github.com/Sheilah-machaha/dsc-phase-1-project-v2-4

## Overview
Microsoft Corporation is a Multinational Technology corporation that deals with software products and operating systems. 
With the current developments and upsurge of the entertainment industry, Microsoft has made a business decision to venture into the movie space, by  creation of a new movie studio. 
An analysis has been done in order to explore the market and come up with insights that will aid in decision making with regards to what type of films to create in the new studio.

## Business Understanding 
There is a need to venture into the entertainment industry and the company has decided to create a movie studio. However, there’s a knowledge gap with regards to creating movies. 
A good analysis will enable the Company make good Business decisions as they venture into this space. 
We need to establish what kind of movies are doing the performing well in the industry. 
Which Movie genres are most popular?
What are the budget requirements in terms of production cost? 
What kind of revenues do the movies generate? 
The findings will enable Microsoft studio know what kind of movies to create.

## Data Understanding and Analysis
# Source of Data
The analysis was based on 3 different movie data sets as csv and tsv files: 
	Rotten Tomatoes Movie info: 1553 records. Timeframe of the data 1997 to 2019
	The Numbers Movie Budgets : 5783 records.  Timeframe of the data:  1975 to 2018
	Box Office Mojo Movies Gross: 3388 records. Timeframe of the data: 2010 to 2018
	In total, 10,724 records. 
 
# Description of Data
The first data set has 3387 records and 5 variables 
We have missing values in some of the columns, Under foreign gross 1350 records are missing. 28 records are missing from domestic gross column and 5 records are missing from the student column.
The second data has 5782 records and 6 variables which are also categorized as columns. There is no missing data. This is good as it shows that we have a clean dataset. 

The third data set has got 1560 records and 12 columns.
Checking for missing values in the dataset

We do have quite a number of missing values. In two of the columns, box office and currency, we have 80% of the records missing data. We therefore choose to ignore the missing values and work with a column that has very minimal missing values. We shall work with genre which has got only 8 missing values which is very minimal, hence we shall ignore the 8 missing as it s less than 1% of the records in that column.


## Visualizations based on the Analysis
We begin our analysis first getting the data for the top 10 studios and plot a graph.

![image](https://user-images.githubusercontent.com/128293656/232339832-18fb7773-5917-4763-b51f-eba6a46c12c2.png)
Observation: Based on the analysis, the top 10 studios (which is only about 4% of the number of number of production studios), produced 37% of the movies (1,268).
## Visualization for the top 10 studios in terms of earnings
![image](https://user-images.githubusercontent.com/128293656/232340044-bbccf330-583f-4eef-ace5-14a4d83fe50c.png)
Observation: A clear observation from the graph is that majority of the studios which were in the top 10 list in terms of number of movies produced, are still in the list for the top 10 for gross earnings. However, some of them have had really high earnings like BV (Buena Vista studio) which was no.7 in production, is currently the highest earning for Total gross revenue.

## Exploratory Data Analysis for the second Dataset.
Checking on the first 10 records based on the way the records have been arranged. Which is in descending order based on the production budget column. From the highest in terms of production cost.

# Movie Budget Analysis
Now we sort the data based on their returns. Meaning, from the top in terms of worldwide gross revenue.

Plotting a scatter plot in order to establish if there is a correlation between production budget and worldwide gross. We based on the top 10 in world wide gross.

![image](https://user-images.githubusercontent.com/128293656/232340137-48ba5650-9433-4df0-bcf4-ab59cf0b501d.png)
Observation: There is a positive correlation between production budget and worldwide gross.
Plotting a graph showing the impact of production budget on worldwide gross and domestic gross. To basically show the Return on investment.
![image](https://user-images.githubusercontent.com/128293656/232340179-f2b37a75-2c36-4018-bac6-6f5d0f5e893e.png)

Observation: The graph clearly shows that a good investment in terms of production budget, yields an increased. The higher the investment on production budget of a movie, there is a significant gain in terms of worldwide gross and domestic gross revenue. The highest being Avatar, which made over 8 times of it’s production budget. The other 4 movies which have had a high ROI are: Titanic, Star War, Avengers & Jurasic World.

Here, we seek to find the top 10 genres which will aid us in making the decision of which kind of movies to be produced.

We plot a graph to show the count of the top 10 genres from the highest genre which is assumed to be the most popular.

Observation: The graph clearly shows that a good investment in terms of production budget, yields an increased. The higher the investment on production budget of a movie, there is a significant gain in terms of worldwide gross and domestic gross revenue. The highest being Avatar, which made over 8 times of it’s production budget. The other 4 movies which have had a high ROI are: Titanic, Star War, Avengers & Jurasic World.

Here, we seek to find the top 10 genres which will aid us in making the decision of which kind of movies to be produced.

We plot a graph to show the count of the top 10 genres from the highest genre which is assumed to be the most popular.

![image](https://user-images.githubusercontent.com/128293656/232340227-8f0402a2-bb31-42e0-9b67-e64b93183bd5.png)
Observation: Drama is the leading genre forllowed by Comedy. These genres seem to be the highest in production, which can be assumed that the viewership of the two genres is also high.

## Conclusion
In conclusion, the analysis sought to investigate some aspects of movies in terms of Genre, Production Budget, gross returns and success of top studios.
Based on the findings of the analysis, the below are the recommendations:
1) A good investment in terms of the movie production budget, has to be set aside, in order to realize good returns in terms of gross domestic and gross worldwide returns. Need to budget in the range of 200 million US 𝑡𝑜425 milllion US dollars.  Meaning that they should focus on high budget movies in order to realize high returns.
2) As the company ventures into this new scene of entertainment, they should mostly focus on Drama and Comedy, as these two are the most popular movie genres.
3) Studios which do a lot of movie productions also get to realize high foreign returns. It would be a good idea to pick learnings from the top two earning Studios (Buena Vista & Universal Studios) as their success overtime, is evident from the analysis. Hence, resourcing needs to be done for the right team to ensure they hit the ground running

## Next Steps
Based on the findings, this would be a good opportunity for Microsoft to venture into this space and recommendations of: investing in a good budget, right genre selection and learning from those who are ahead in the industry. This will definitely ensure that the studio is beginning on the right footing toward the path of success.







