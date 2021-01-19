# TV-Popularity
There are about 4000+ rows and 16 columns. Cvt_per_day is a measure on how much a movie is consumed by the audiences per day. Higher number means the movie is more popular on our platform.

The following are the descriptions of the columns:
Video_id: A unique ID for a movie
Cvt_per_day: Cumulated view time per day
weighted_categorical_position: Average vertical positions on the home page that the movie was placed
weighted_horizontal_position: Average horizontal position on the home page that the movie was places
Genres: genres of the movie
release_year: the year the movie was released
imdb_votes: the number of votes oN IMDB, typically higher the votes the better
budget: budeget of the movie production, typically the higher the better
boxoffice: gross box  office in US as updated on IMDB, typically the higher the better
imdb_rating: ratings on imdb
duration_in_mins: how long is the content in minutes
mpaa: MPAA ratings
Awards: TVPG ratings
Import_id: Content pertners
Metacritic_score: Metacritic score on IMDB page. Typically, the higher the better
Star_category: A score to measure how popular the actor/actress are associated with the movie


Object: Build a prediction model to predict whether a movie is going to perform well on our platform (cvt_per_day) based on the information in the dataset
