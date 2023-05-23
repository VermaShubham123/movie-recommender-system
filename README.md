
## Project Title: Movie Recommender System

## Project Description:
This project aims to develop a movie recommender system that suggests movies to users based on their preferences and similarities to other movies. The system utilizes two dataset of movies containing information such as budget, genres,	keywords,	original_language,	original_title,	overview,	popularity, release_date,	revenue,	runtime, spoken_languages,	status,	tagline,	title,	vote_average,	vote_count, movie_id,	cast and	crew.

Here we have to merge two datasets of 5000 movies and then prepare the data into a useful form for ML model after pre processing the data and finds the useful features by feature enginering and used stemming technique for reducing words to its stem that affixes to suffixes and prefixes or to the roots of words known as "lemmas". Then we change text to vector by technique 'Bag of words'.And finally using 'Cosine Similarity' we calculate distances and find out the nearest vectors(movies).
