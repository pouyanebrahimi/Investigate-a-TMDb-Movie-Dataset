# Investigate a TMDb Movie Dataset
## by Pouyan Ebrahimi


## Dataset

> The data set contain information about 10866 movies and reported 21 different features of them including:id, imdb_id, popularity, budget, revenue, original_title, cast, homepage, director, tagline, keywords, overview, runtime, genres, production_companies, release_date, vote_count, vote_average, release_year, budget_adj, and revenue_adj


## Summary of Findings

1. Overal, by far the popularity of Adventure and Science Fiction movies are higher than others and are respectively ~1.2 and ~1. The popularity of Documentary, Foreign and TV Movie are almost the same and are the least popular movies. The popularity of the rest of genres are between 0.4 and 0.8.

2. In general, the popularity of movies has been increasing gradually from ~0.4 in early 1960 to ~0.6 in first decade of 20th century. In 2014 and 2015, there is a tremendous surge in popularity of movies from ~0.6 to more than 0.9.

3. The popularity of genres is fluctuating every year. But in some years some genres are surging, for example in 1997, the popularity of Adventures movies increased dramatically from <1 in 1976 to around 4 in 1977. You can take a look at other graphs as well.

4. By increasing the popularity the revenue increases.

5. By increasing budget, the revenue increases!

Limitations
1. The assumption that I used is very strong and basically I am not considering the fact that each movie may have different geners.
2. The popularity is based on collected information in developed countries that everyone has a free access to the movie links such as IMDB. The popularity may only represent the opinion of some countries. That would be nice we have some more information about number of votes from different countries.
3. There are many old movies in that not many people watched them. By the way, right now all young people are using internet every day. That would be very helpful to have some other columns regarding the age and gender of people who vote for movies.
4. It was very challenging to visualize the genres, release year and popularity at the same time.
