# Movie Data Analysis
I. Objectives: 
The goal of our analysis is to analyze the box office,Facebook likes and imdb score based on directors, actors or actress, genres,plot keywords and geography to project forward what are the key factors to the success of a movie and are there any patterns or correlations among those key factors.We are going to answer the following questions:
●	Who are the top 5 directors by box office and top 5 favorite directors via Facebook and IMDB?
●	What is the best grossing duration for a movie?
●	Who are the top 5 actors/actresses by box office or Facebook likes? look for overlap in lead/supporting. weigh lead as highest
●	What are the top 5 Plot Keywords?
●	What are the top 3 countries that made the most movies? 
●	Are the countries that made the most movies the same as the countries having the highest box office?
●	Are the highest grossing movies PG-13 or PG
●	What are the top 5 genres based on the top 100 movies by gross, facebook likes and imdb score?

II. Data Preparation
https://www.kaggle.com/datasets/karrrimba/movie-metadatacsv
This data is of good quality, we may need to remove some null values and duplicated values and otherwise, it is all good to make analysis.
We will use Pandas to do analysis. The biggest challenges might be the box office by movie genres and plot keywords, as one movie has multiple genres and plot keywords, we need to rebuild the data and make only one genre or plot keywords  per cell in order to better calculate the total numbers or revenues

III. Analysis
Since the original data is from 1916 to 2016, we decided to narrow down the data from 2005 to 2016 (about the last 10 years) in order to better represent the modern film viewing public. We then looked at directors, duration, actors,plot keywords, countries, content rating and genre and how they could influence a movie's success.

IV. Conclusions
Directors:
In conclusion we can find that just because a director is well liked on Facebook or has a large amount of likes across all their movies, it does not mean that their movie will be a box office success. This could be due to the directors having a more niche audience that isn’t applicable to the larger population. So in terms of trying to make the largest grossing movie possible, a director that has made well grossing movies in the past should be chosen over a director that is more well received on Facebook or imdb as they show they have the ability to appeal to the larger audience and bring in the most amount of people even if the movie is not as good.

Genres:
The movies related to Adventure, Action and Fantasy drive the highest box office, while Drama and Thriller are relatively less contributed to  the box office, however, these types of movies are popular or more likely to be favored by internet audiences. So overall, if a movie contains at least three genres from adventure, action, drama, Sci-Fi and thriller, it would be a successful movie.

Actors:
The top actors based on the features analyzed and their respective weightings were found to be:
Lead actor: CCH Pounder
Supporting actor: Tom Hardy
Second supporting actor: Joseph Gordon-Levitt 
Content Rating, Impact of Countries
There are higher chances of having a top grossing movie from a country which makes the most movies. Also the majority of the movies which grossed the most are PG-13. Hence it points in the direction for a movie to be grossing. We need PG-13 material as the majority of the movies were PG-13. Hence there are more chances of a movie made in the USA and PG-13 would help boost the sales of the movies.

Plot Keywords:
The proposed film should have the following elements:set in a high school,significant characters should include a coach (achievable, given the setting) and a baby and also the main theme should involve faith.  Given the findings from the genre, the final plot elements should either be demons, taking the proposed movie in the direction of a supernatural adventure fantasy, or police, suggesting a more grounded action movie.



