![readme header](https://github.com/LeoBulcsu/ETL_250_Best_Movies/assets/136447924/8be46668-0d71-42b6-9486-04d3e5b36c35)


# ETL project: 250 Best Movies
An audience-focused movie list.

## Chapter 1: The Project.

This project is not only an ETL project, it is an idea that has been in the minds of all of us who have, at some point in our lives, wondered which is the best film ever. 

I have dedicated the last fifteen years of my life to the film industry. There is probably a consensus that the best movie is the one that you like the most because each of us experiences films differently. Still, since there are critics and websites dedicated to ranking movies all over the world, I decided to create a ranking that doesn't source from only one website but to some of the most influential sites on the World Wide Web.

I decided to create my database focused on those "influential" sites: **IMDB, Rotten Tomatoes, Metacritic and TMDB (The Movie DataBase)**.

My starting point was IMDB, probably the most famous of them all and from their list of the 250 Top Movies, I decided to compare their ranking to the rest of the reviews movie sites. I apologise to all of you who believe that **"The Shawshank Redemption"** is the best movie ever made, but 

![TSR_giphy](https://github.com/LeoBulcsu/ETL_250_Best_Movies/assets/136447924/91480d27-aede-4372-b1c7-719be28c7f0b)



## Chapter 2: The Muscle (Extraction and Transformation).

For this project, I have tried to use as many extraction tool methods as possible and I must say I have had a lot of fun with **Selenium**, seeing my computer doing stuff on its own is something that seems like witchcraft. I have used it for IMDB and Rotten Tomatoes. 

I have also found an **API** called TMDB that contains lots of movie info. I have taken scores from there too and also from some documents that I have found in Kaggle about Metacritic's reviews. 

After extracting the info I cleaned those data frames that needed a bit of a touch-up but all and all the info I retrieved from the internet was made ad-hoc, so that has not been a biggie.

With a little bit of magic and after glueing up a few things together I ended up with a very interesting data frame that I uploaded it to MongoDB with the hope that I will make it bigger, fatter and better with time.

## Chapter 3: The Verdict.


<img width="920" alt="BFilms_bestMovies" src="https://github.com/LeoBulcsu/ETL_250_Best_Movies/assets/136447924/b0e176b4-8370-45fd-a261-8e9113f948d4">

![the-god-father-marlon-brando](https://github.com/LeoBulcsu/ETL_250_Best_Movies/assets/136447924/0b79cc36-ea5e-4c1d-889d-9faa5661c7e6)

### Resources:

https://pandas.pydata.org/docs/

https://www.selenium.dev/selenium/docs/api/py/api.html

https://www.imdb.com/chart/top/

https://www.rottentomatoes.com/

https://www.themoviedb.org/

https://www.kaggle.com/datasets/miazhx/metacritic-movie-reviews

https://view.genial.ly/6549d86b33c521001117a612/presentation-etl-250-best



