# MOVIES ANALYSIS
This analysis is aimed at helping come up with concrete recommendations of starting a movie studio for Microsoft Company. Microsoft wants to start a movie business hence the recommendations will help in the success of the movie business. 

## Datasets used
In this analysis, I used 3 datasets namel;
The data for this analysis comes from;
* ```im.db```: 
This is a SQLite database that consists of data about movies from IMDB. The data consists of 8 tables. For this analysis I will only use 2 tables i.e. ```movie_basics``` and ```movie_ratings``` table.
*  ```bom.movie_gross.csv```: 
This is a csv file that contains data about movies from Box Office. 
* ```tn.movie_budgets.csv```: 
This is a csv file that shows the budgets allocated to each movie and the income generated from the movie.

## Data Cleaning
Some of these datasets have missing values and also have duplicates. I did data cleaning on the data so as to be able to analyse it.

## Data Analysis
After analysis of the data, I was able to see some key findings on the data which are;

### Budget and gross profit
It is noted that there is a slight positive relationship between budget and the gross profit. The budget you allocate to the movie determines the profit you'll get from the movie. The higher the budget, the higher the profit.

![ alt text for screen readers]("Budget and gross profit.png") 

### Genres with highest profit
Some genres also appeared to have a higher profit than others hence it would be best to invest in them.

![ alt text for screen readers]("Highest profit making genres.png")

## RECOMMENDATIONS
* Microsoft should consider producing movies of genres ```'Adventure, Drama'```, ```'Comedy, Drama'``` or ```'Adventure, Comedy'```. A combination of these genres seem to have a very high rating and also have a high profit.
* Consider using a budget of over 10 million dollars. The more resources you allocate to a movie, the higher the profit.
* Microsoft should not concentrate on just producing a lot of movies because the number of movies produced by a studio does not contribute to an increase in the income of the studio. They should aim at producing the genres with a high rating as well as a high profit.

