# nfl-fandom
![Fandom](https://github.com/vavaidya/nfl-fandom/blob/master/Fandom%20Img.jpg)
## INTRODUCTION
The NFL made revenues of $22B over the 2018 season and is nearing revenues of $25B in 2019. Revenues are based on a business model with two parts: national revenue and local revenue.
National revenue include TV deals, Merchandising and Licensing while Local revenue streams include Ticket Sales, Concessions and Corporate Sponsors.

## PROBLEM TO SOLVE
The NFL has been investigating new markets to expand into, location is extremely important - an expansion team’s success is therefore heavily dependent on local fans. The project seeks to analyse how successful an expansion team would be in a new location and make a recommendation of where to expand for the NFL.

## APPROACH AND CONCEPTS
* **Web Scraping Tweets** - Used *Tweepy* and Python's *Get Old Tweets* package to extract tweets with #NFL
* **Secondar Data** - Extracted top 100 populous cities and NFL teams and location data
* **Data Preprocessing** - Performed lemmatisaton, stop-word removal, tokenisation, capitalisation/lowerising
* **Sentiment Analysis** - Used *VADER* Sentiment Analyser to give a 'Passion Score' to cities based on passionate tweets
* **Topic Modelling** - Grouped cities based on common topics they tweeted about, picking three major categories Betting, Watching and High Spirits(get that ?)

## RESULTS
* London is the most attractive market based on passion and market size - the NFL should target this location for its next team location
* Jacksonville is the least attractive market of any location with a team and could be a candidate for moving to London (interestingly Jacksonville has played in London each year from 2013 and treats these games as ‘home’ matches) 
* Toronto is the second most attractive market based on passion and market size - the NFL should begin to hold games in Toronto to prepare it for further possible expansion

## LEARNINGS
* User Generated Content has immense applications
* Getting good raw data for analysis is the pain point and majority of time is spent cleaning the data properly
* Its important to have some context around the problem and objective and build some hypothesis. The analysis should then be a tool to prove/disprove it significantly

## REPOSITORY DETAILS
Access -
1. [Teams_Cities_Stadiums](https://github.com/vavaidya/nfl-fandom/blob/master/Teams_Stadiums.ipynb) - Code to create base data set with different NFL teams, cities with their stadiums and population
2. [Tweets Cleaaning and Preprocessing](https://github.com/vavaidya/nfl-fandom/blob/master/Data_setup_v1.ipynb) - Code to clean tweets and perform stop-word removal, lemmatisation, capitalise/lowerise, tokenisation etc.
3. [Sentiment Analysis](https://github.com/vavaidya/nfl-fandom/blob/master/NFL%20Sentiment%20Scores.ipynb) - VADER sentiment analyser
4. [Similarity Topic Scores](https://github.com/vavaidya/nfl-fandom/blob/master/Similarity_all.csv)
5. [Final Presentation - Summary of Approach and Results](https://github.com/vavaidya/nfl-fandom/blob/master/NFL%20Presentation.pdf)
6. [Raw Data](https://github.com/vavaidya/nfl-fandom/tree/master/data)
