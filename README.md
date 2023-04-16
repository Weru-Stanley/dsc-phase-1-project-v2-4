# DSC PHASE 1 PROJECT 

This is is an academic project. I was required to analyse and derive findings and give a recommendation  to Microsoft studios. 

## Business Understanding.

The movie production space is flooded with many creators and different types of genres that can be created. From general knowledge some of the key varibales in movie production include budget and runtime of the movie. The budget significantly determines the quality of work that will be produced. Runtime infuences the amount of resources used and also how the viewers interact with the production.Long and short movies result in varying levls of viewer engagement which is key to determinig sales. In this project , I sought to establish the cheapest and most expensive genres to produce, the most profitable genreae and to establish if some of the mentioned correnations are indeed true.


### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### Business Questions

1.Which is the best rated genre; most profitable genre, genre with highest ratings?
2.Which are the most expensive genres and cheapest genres to produce?
3.What is the correlation between runtime and ratings?
4.What is the correlation between runtime and budget?
5.Which are the studios with the most productions ?

## Data Understanding and Analysis

### The Data

The relevant date for our analysis was obtained from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
From box office MOjo, I obtained data on worldwide gross sales and budget,/

* [IMDB](https://www.imdb.com/)
From Imdb, I obtained data on average ratings, runtime and genres

I combined the data into a dataframe (combined_movies_data) and utilised its copy for analysis. 

#Conclusions.
From the analysis, the a number of conclusions can be made based on the leading questions.

- The best rated genre is Drama and Action,Adventure,Sci-Fi.
![Best Rated genred](https://user-images.githubusercontent.com/128227310/232332499-ff62695e-50b5-4472-9629-f4a4614c0d63.png)
- The most profitable genre is Action,Adventure,Sci-Fi.
<img width="677" alt="Most profitable genre" src="https://user-images.githubusercontent.com/128227310/232332825-3f612ca0-d2ca-41de-a493-854656d9de52.png">
- The cateogory of action adventure movies are the most expensive to produce. Action,Adventure,Sci-Fi. being the most expensice action adventure movie to produce
- Drama, comedy and thriller movies are the cheapest to produce.
- There is weak positive correlation between budget and runtime. 
<img width="432" alt="Runtime VS Budget" src="https://user-images.githubusercontent.com/128227310/232332707-79520aeb-2a76-43e5-ab44-1f3dfc34aab4.png">
- There is weak positive correlation between ratings and runtime.
 <img width="307" alt="runtime vs rating" src="https://user-images.githubusercontent.com/128227310/232332532-4ba0f57e-ba18-4ada-806e-47dd48524631.png">
- Universal studios and Fox studios have produced the most movies.

 ## Recommendations.
 Base on the business problem and the findings, I recommend that:

1.Microsoftstudios can choose to produce either Drama or Action,Adventure,Sci-Fi.

Microsoft studios can start by producing drama movies and variation like darma, comedy, animation since they are cheap to produce and relatively profitable compared to other genres and they have good ratings. After increasing viewership of their movies, Microsoft studios can proceed to produce Action,Adventure,Sci-Fi which is the most profitable but expensive to produce.

2.Microsoft should commission another study to recommend the best distribution channel for its movies. We could not do this since the data was not available.

3.Later on Microsoft studios should consider a study on the market share and how acquiring smaller independent studios would help them grow their market share and viewership.

