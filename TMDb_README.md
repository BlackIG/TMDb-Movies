# TMDb - Investigate a movies dataset

## by Ikechukwu Chilaka

## Dataset
> This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue. from 1960 to 2015, The dataset has 21 columns and 10866 rows in all. 

>**'id' and 'imdb_id':** which are unique identifiers of the movies, 

>**'popularity':** how popular the movie is amongst viewers; a metric that boosts search results 

>**'budget' and 'revenue':** the budjet and income without accounting for inflation 

>**'original_title'and 'cast':** the title of the movie and the lead actor(s)

>**'homepage':** website to see the movies landing page, 

>**'director', 'genres', 'production_companies':** info on the name of the directors, the movie genre, and production companies

>**'tagline':** short text which serves to clarify an idea for, or is designed with a form of, dramatic effect. 

>**'keywords':** keywords associated with the movie to allow for easy search, 

>**'overview':** brief plot summary

>**'release_year':** year of movie release, **'release_date':** date of release **'runtime':** duration of movie in mins

>**'budget_adj', and 'revenue_adj':** show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time.

>**vote_count** represents the number of users who voted while **vote_average:** what the voters voted on a scale on 1-10

Link:  https://www.kaggle.com/tmdb/tmdb-movie-metadata.

## Key Questions

>**Does the length of the movie affect the movie's  profitability?**

>**Do movies with better more user engagement mean more income?**

**a.What genre are these movies?**

**b.The day which the movie is  released (weekend or weekday) could also affect user engagement**


## Summary of Findings

>**Does the length of the movie affect the movie's  profitability?**

Although I can't say that length of movie affects profitability directly. We can seee that longer movies are not popular amongst viewers, and we can also see that popular movies tend to be profitable.

Generally speaking, movies in the range of 100 to 125mins showed more popularity

>**Do movies with better more user engagement mean more income?**

**a.What genre are these movies?**

I discovered that the popular genres are not being produced much, because of this, it was difficult to draw conclusions on them as their size was small. But Fantasy and Action are really unexplored genres as they show promise

Most produced genre(Drama, Comedy, Thriller, Action), 

Most popular amongst viewers: (Adventure, SciFi, Fantasy, Action)

**b.The day which the movie is  released (weekend or weekday) could also affect user engagement**

Most movies are released on Friday. This was observed across the genres

>**Limitations**

More than half of this dataset has income calculation as zero. My analysis was based on this error as the rows were too many to drop