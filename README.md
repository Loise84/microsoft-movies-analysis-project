# microsoft movies analysis project

## Business Understanding
### *Introduction*
Microsoft has decided to venture into the movie industry by establishing a new movie studio. However, they lack expertise in creating films and are uncertain about the types of movies that are currently performing well at the box office. To make informed decisions about the content they should produce, they need insights into the most successful genres in the film market.

### *Problem Statement*:
Microsoft's new movie studio lacks knowledge about the current film market trends and successful genres. They need to explore the types of films that are performing the best at the box office to guide their decision-making process and determine what kind of movies they should create.

### *Main Objective* :
The main objective is to identify the top-performing film genres at the box office and provide actionable insights to Microsoft's new movie studio head. These insights will help them decide what types of films to create to maximize their chances of success in the movie industry.

### *Specific Objective* :

* Analyze the box office performance of different film genres.
* Identify the genres that have been consistently successful over a specific time period.
* Evaluate audience preferences and market demand for various film genres.
* Provide actionable recommendations to the head of Microsoft's new movie studio based on the findings.
### Data Understanding

The data sources for this analysis will be pulled from the following files:

####  files involved.

* **Source**: This dataset comes from: <a href="https://www.boxofficemojo.com/">box office Mojo</a>,<a href="https://www.rottentomatoes.com/">Rotten tomatoes</a>,<a href="https://www.themoviedb.org/">The movie DB</a>,<a href="https://www.the-numbers.com/">The Numbers</a>
1. `bom.movie_gross.csv`
* **Contents**: It contains data of :the title of movies released plus the studio that released it,plus domestic gross and foreign gross.
* **Format**: CSV data, where each row contains a movie title, studio, domestic_gross,foereign_gross and year
2. `imdb.title.basics`
* **Contents**: It contains data of : movie id, movie title, start year ,runtime minutes ,genres
3. `imdb title.ratings`
* **Contents**: It contains data of : movie id,average ratings , numvotes.

## Data visualizations
<img src="images/top 10 genres by foreign gross sum.png" alt="Visualization">
<img src="images/top 10 genres by domestic gross sum.png" alt="Visualization">
<img src="images/top 10 genres by average rating.png" alt="Visualization">
<img src="images/Comparison of top 10 genres and number of votes.png" alt="Visualization">

###  CONCLUSION

1. ## Did we have the right data ?
    YES : THE AVAILABLE DATA HELPED SOLVE THE TASK.
    HOW?
     I was able to: a. group the movies according to the particular genres
                    b. calculate the domestic gross and foreign gross generated by each genre and compare
                    c. identify the genre with the highest average ratingsand compare to the number of votes.
2. ## Solution to the task:
   from the analysis, a combination of action,adventure and sci-fi  genres have proved to 
    * a. generate a high domestic and foreign gross.
    * b. have higher ratings than the other genres
    * c. attain a higher numvotes count than other genres.

 ### recommendations
* 1. Focus on Action, Adventure, and Sci-Fi Genres: These genres have proven to be highly successful in terms of generating both domestic and foreign gross. They also have higher average ratings and a higher number of votes compared to other genres. By prioritizing movies in these genres, the business can increase its chances of success.

* 2. Invest in High-Quality Productions: Since movies in the recommended genres tend to receive higher ratings and attract more votes, it is crucial to invest in high-quality productions. This includes hiring talented directors, writers, and actors, as well as ensuring top-notch production values. By delivering exceptional movies, the business can build a reputation for producing engaging and well-made films.   

* 3. Market Strategically and Target Global Audiences: The analysis showed that movies in the recommended genres tend to perform well both domestically and internationally. To maximize success, it is important to develop effective marketing strategies that target global audiences. This can involve localized advertising campaigns, international distribution deals, and utilizing digital platforms to reach a wider audience. By expanding the business's reach beyond domestic markets, it can tap into the global demand for action, adventure, and sci-fi movies.

#### By implementing these recommendations, the business can increase its chances of success by capitalizing on the popularity and profitability of the recommended genres, delivering high-quality productions, and effectively reaching global audiences.
###  canvas presentation
https://www.canva.com/design/DAFkOmLN1zo/cFTXZ9YxE5C8lVcBtUueaw/edit?utm_content=DAFkOmLN1zo&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton