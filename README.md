**Sentiment Analysis: Identifying Negative Reviews**
This project is all about spotting negative reviews using advanced techniques that analyze the feelings expressed in text. We're diving into a dataset packed with info about movies and their reviews. Our mission? To prep the data, dig into its details through some data exploration, and teach machines to tell whether a review is a downer or a thumbs-up.

**Features We're Looking At**
tconst: Each movie gets its own special ID, like a secret code.
title_type: Tells us what kind of title we're dealing with – is it a movie, a short film, or something else?
start_year: The year the movie hit the screens or started streaming.
is_adult: A little binary flag that tells us if it's a grown-up movie (1) or not (0).
average_rating: The IMDb rating average for the movie.
review: This is where users pour out their thoughts on the movie.
pos: A special label that says if the review is positive (1) or negative (0).
How We're Getting Ready
We start by checking if anything's missing or if there are any copies lying around in the data. Then, we tidy up the reviews by making sure they're all lowercase and only have letters – no funny characters.

**What We've Discovered So Far**
We're like detectives, digging into the data to find out what's what:

We've figured out how many movies came out each year.
We've counted how many reviews each movie racked up.
We've even looked at how a movie's rating changes based on the number of reviews.

**Putting Our Models to the Test**
We've trained our machines to learn from the data and tell us if a review is negative or not. We've tried out three different models – Logistic Regression, LGBM Classifier, and Random Forest Classifier. We've put them through their paces and checked how well they perform using a few different measures.

**What We've Learned**
After all our experiments, we've found that Logistic Regression is the real champ. It's super reliable and can predict whether a review is negative or positive with impressive accuracy. But hey, there's always room for improvement! We're open to new ideas and welcome anyone who wants to join in and make this project even better.

Got any questions or want to chat? Drop your valuable suggestions. 
