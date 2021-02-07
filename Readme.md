# FIFA 21 players Data Exploration
## by Lyonel

Soccer is one of the most popular sports in the world. Although it is a physical and endurance sport, the technical dimension is emphasized. Just look at the most scrutinized and celebrated players. Moreover, the challenge for the teams is to be competitive both sportily and financially. Thus the transfer market is one of the great moments in a season because contracts and salaries are negotiated based on the overall evaluation of the players.

Thus we have chosen to answer 4 major questions in this study:

- Are the most technical players the most offensive players on the field?
- Are there underpaid players considering their overall rating? Are there overpaid players as well?
- What are the major variables that predict a player's salary given the competition for their position?
- Which teams overpay their players considering their overall rating?

## Dataset

The data consisted of attributes of all 18944 players from the latest edition of FIFA 21. Attributes include Club, DateOfBirth, Value, Salary, statistics such as Attacking, Skills, Defense, etc. 
Considering our 4 research questions, we retained only field players. Because keeping goalkeepers would require us to take into account other variables that are completely different from those of the field players. The final dataset contains 16654 players and 63 features.
The dataset can be found on Kaggle platform [here](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset?select=players_21.csv) with feature documentation available [here](https://www.kaggle.com/stefanoleone992/fifa-21-complete-player-dataset).



## Summary of Analysis

We began our study with a phase of data exploration and data cleaning in order to have data ready for analysis.
The cleaning consisted essentially of :
- The handling of missing values
- Conversion of data to other formats
- Removing unneeded rows and columns
- The creation of new fields necessary for our analysis

We then proceeded to analyze our data to answer the questions asked.
We chose to answer the first two questions using graphs (scatterplot and boxplot). The results found confirmed our hypotheses. 
For the 3 and 4 questions, we used a linear regression alogorithm to make the predictions. 

Some operations were performed to refine our charts in the presentation:
- The use of data sampling to polish our presentation by keeping only 10% or little more of the data. This allowed us to better highlight the points that we put forward in our analysis, especially in the scatterplot.
- The use of an almost unique color palette with some color additions on some graphs. This made it possible to make more coherent and more pleasant our presentation as a whole.


## List of resources

- Stackoverflow
- python-graph-gallery.com
- coolors.co 
- seaborn.pydata.org
- Kaggle.com for data gathering