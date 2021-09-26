# Injuries of professional NBA players
## Background
In the summer heading into my senior year of high school, I researched the correlation between height and knee injuries for NBA players between 2010-current day. I did this under the mentorship of a college student who has experience in the field of data science. The reason I chose a project relating to NBA injuries is watching sports is one of my passions and I was curious to see why taller players are the ones that are getting carried off the court/field in sporting events. The one injury that sparked this curiosity was Kristaps Porzingis' knee injury (torn ACL) because my initial thoughts were that he got hurt due to him being 7'3". This study can be used to determine the longevity of future NBA players, future negotiations between players, or likelihood of getting injured again. 
## Brainstorming
The beginning of the project started out as brainstorming the topic of my research project as I knew I wanted to research something related to NBA injuries but was unsure what exactly. I had to come up with all the potential quantitative and qualitative variables that I could possibly do research on. My initial list of variables was approximately 30 possible projects but I gradually narrowed down the topic choice based on what interested me and if there is enough data that exists to perform the research. 
## Data Engineering
First I input the libraries which were numpy for linear algebra and pandas for data processing. Next I used the read function to convert the CSV files of the NBA players and injury history datasets into pandas dataframes. The next step was to have a season which was only 1 number (convert 2010-11 season for example to 2010) and I assigned that to a variable called adj_season. I then combined the dataset of the injured players and all players into a new dataset. I did this to find the heights and weights for each player and correspond it to the injuries suffered by the player. After the combining of the datasets, I created a column that counts injuries and I assigned it to a value of 1. Then I created a deep copy with only the players that played after 2010. After I dropped adjusted season. I did this to get the players that aren't injured from 2010-20. I then created a list of dataframes containing injured and non injured players. Following that, I concatanated the list to get both groups together. In one of the final steps, I wanted to determine what I would consider tall. I concluded that I would determine tall as being in the 75th perceintile or higher in terms of height. Finally I converted this dataset to a CSV file so I can do an analysis on this data enginerering.
![test](/Data engineering.png)

[NBA Injuries Data Engineering] (https://www.kaggle.com/thomaspequegnot/nba-injuries-project)
## Analysis
After all the data engineering, I ran a data analysis on my code using the language r as it is a strong language for statistical analysis. My mentor and online tutorials helped me with this part of the project since I had no experience coding in r prior to the project. The two statistical methods I conducted were a hypothesis test and a confidence interval. The hypothesis test and confidence interval showed statistical significance that there was in fact strong evidence to conclude that tall players are more prone to suffering knee injuries than short players.

[NBA Injuries Hypothesis Test] (https://www.kaggle.com/thomaspequegnot/hypothesis-testing/edit/run/74061825)

[NBA Injuries Confidence interval] (https://www.kaggle.com/thomaspequegnot/confidence-interval/edit/run/74063575)
## Conclusion
After all the data I gathered and the statistical analysis tests I ran, I concluded that there was strong statistical significance between tall players and high likelihood of knee injuries.

![test](/P-value_hypothesis_testing_graph.png)


#### references
- [modern dive tutorial](https://moderndive.com/)
- [NBA injuries dataset] (https://www.kaggle.com/ghopkins/nba-injuries-2010-2018)
- [NBA players dataset] (https://www.kaggle.com/justinas/nba-players-data)
