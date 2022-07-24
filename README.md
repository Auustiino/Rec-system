
# Movie Recommendation System

By: Austin Boring

## Summary
The Goal here is to create a movie recommendation system, outputting recommendations based on two different inputs. The first input being a string movie title, outputting most similar movies based on user rating data. The second input being a series of movies rated by the user, to output most similar movies based on this users ratings paired with all other user ratings. 

## The Data 
Data was pulled from the grouplens movielens data base, a non-commercial movie recommendation platform run by the University of Minnesota. 

## Modeling 

6 Different Models were trained and evaluated with SVD++ outperforming all others

<img src = 'Report/recc-sys-base-cv.png' alt = 'MAE' height = '400' width = '600'>

## Metrics

The tuned model was able to achieve a Mean Absolute Error of 0.64  
<br>
<img src='Report/MAE.png' alt='MAE' height = '400' width = '600'>
<br>

with a pearson correlation of 0.59 between predicted and actual ratings
<img src = 'Report/Pearson-corr.png' alt = 'Pearson Correlation' height = '400' width = '600'>

## Recommendation Examples
Example using a movie title input
<br>
<img src = 'Report/title-in-1.png' alt = 'rec1' height = '' width = ''>
<br>
And an example using user inputted ratings
<br>
Ratings:
<br>
<img src = 'Report/rec-from-rating.png' alt = 'rec2' height = '400' width = '600'>

Recommendations:
<br>
<img src = 'Report/rated-movies.png' alt = 'ratings' height = '' width = ''>
