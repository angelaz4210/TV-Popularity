# TV-Popularity
There are about 4000+ rows and 16 columns. Cvt_per_day is a measure on how much a movie is consumed by the audiences per day. Higher number means the movie is more popular on our platform.

The following are the descriptions of the columns:  
<br />Video_id: A unique ID for a movie  
<br />Cvt_per_day: Cumulated view time per day  
<br />weighted_categorical_position: Average vertical positions on the home page that the movie was placed  
<br />weighted_horizontal_position: Average horizontal  position on the home page that the movie was places
<br />Genres: genres of the movie
<br />release_year: the year the movie was released
<br />imdb_votes: the number of votes oN IMDB, typically higher the votes the better
b<br />udget: budeget of the movie production, typically the higher the better
<br />boxoffice: gross box  office in US as updated on IMDB, typically the higher the better
<br />imdb_rating: ratings on imdb
<br />duration_in_mins: how long is the content in minutes
<br />mpaa: MPAA ratings
<br />Awards: TVPG ratings
<br />Import_id: Content pertners
<br />Metacritic_score: Metacritic score on IMDB page. Typically, the higher the better
<br />Star_category: A score to measure how popular the actor/actress are associated with the movie


Object: Build a prediction model to predict whether a movie is going to perform well on our platform (cvt_per_day) based on the information in the dataset
