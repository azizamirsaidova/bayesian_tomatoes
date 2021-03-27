# Bayesian Tomatoes
This lab will cover:  
* Making and interpreting predictions from a Bayesian perspective 
* Using the Naive Bayes algorithm to predict whether a movie review is positive or negative 
* Using cross validation to optimize models

Rotten Tomatoes gathers movie reviews from critics. An entry on the website typically consists of a short quote, a link to the full review, and a Fresh/Rotten classification which summarizes whether the critic liked/disliked the movie.

When critics give quantitative ratings (say 3/4 stars, Thumbs up, etc.), determining the Fresh/Rotten classification is easy. However, publications like the New York Times don't assign numerical ratings to movies, and thus the Fresh/Rotten classification must be inferred from the text of the review itself.

This basic task of categorizing text has many applications. All of the following questions boil down to text classification:

* Is a movie review positive or negative?
* Is an email spam, or not?
Language is incredibly nuanced, and there is an entire field of computer science dedicated to the topic (Natural Language Processing). Nevertheless, we can construct basic language models using fairly straightforward techniques.
