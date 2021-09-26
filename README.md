# Injuries of professional NBA players
## Background
In a 17 year overview, it was concluded there was no correlation between injury rate and any demographics between NBA players. Despite this, my instinct told me this was wrong because I believed taller players are more likely to be injured. The one injury that sparked this belief was Kristaps Porzingis' knee injury (torn ACL) because my initial thoughts were that he got hurt due to him being 7'3". My instinct motivated me to research and perform an analysis to see if tall players specifically are more likely to suffer knee injuries than other players. The analysis I conducted can be used to determine the longevity of future NBA players, future negotiations between players, or likelihood of getting injured again. 
## Brainstorming
The beginning of the project started out as brainstorming the topic of my research project as I knew I wanted to research something related to NBA injuries but was unsure what exactly. I had to come up with all the potential quantitative and qualitative variables that I could possibly do research on. My initial list of variables was approximately 30 possible projects but I gradually narrowed down the topic choice based on what interested me and if there is enough data that exists to perform the research. 
## Data Engineering
![test](/Data_engineering.png)

[NBA Injuries Data Engineering] (https://www.kaggle.com/thomaspequegnot/nba-injuries-project)  <-- full details can be found in my kaggle notebook
## Analysis

![test](/P-value_hypothesis_testing_graph.png)

I took 10 years of player data and separated the players by height. The 75th percentile or higher would be classified as tall players. I generated the different scenarios in which the null distribution would be true in which tall players are equally likely to suffer knee injuries as the other players. In the context of our generated sampleset, the p-value indicates that taller players are more likely to suffer a knee injury. 

![test](/Confidence_interval.png)



![test](/Hyp_test.png)


[NBA Injuries Hypothesis Test] (https://www.kaggle.com/thomaspequegnot/hypothesis-testing) <-- full details can be found in my kaggle notebook

[NBA Injuries Confidence interval] (https://www.kaggle.com/thomaspequegnot/confidence-interval) <-- full details can be found in my kaggle notebook
## Conclusion
Although the 17 year overview found no correlation between injury rate and demographics of NBA players, my analysis concluded there was in fact a correlation between height and likelihood of suffering a knee injury.




#### references
- [modern dive tutorial](https://moderndive.com/)
- [NBA injuries dataset] (https://www.kaggle.com/ghopkins/nba-injuries-2010-2018)
- [NBA players dataset] (https://www.kaggle.com/justinas/nba-players-data)
- [17 year overview] (https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3445097/#:~:text=The%20incidence%20of%20injury%20was,NBA%20experience%20(Figure%201)
- [p-values] (https://www.amstat.org/asa/files/pdfs/p-valuestatement.pdf)
- [Data types] (https://www.mayo.edu/research/documents/data-types/doc-20408956#:~:text=Examples%20of%20quantitative%20characteristics%20are,are%20also%20called%20categorical%20variables)
- [variables] (https://dpl6hyzg28thp.cloudfront.net/media/Springer_-_Journal_Sports_Medicine._Vol._40_Issue_7_2010.pdf)
