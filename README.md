# Microsoft Movie Studios- Industry Analysis
<img src="https://logos-world.net/wp-content/uploads/2020/09/Microsoft-Logo.png" width="400">
### Author: Adam Pell

# Overview

This projcet analyzes movie data to provide three actionable business recommendations for Microsoft as they look to make an entry into the film industry.

Descriptive analysis of budget, genre, runtime, and revenue data shows that multiple movies across a wide array of budgets, genres, and runtimes is most likely to balance high revenue with strong returns. Microsoft can use this analysis to inform their financial and creative decisions as their new studio looks to gain market share in a highly competitive space.

# Business Problem

Microsoft wants to make an effective entry into the movie business. To do so, there are many crucial decisions that will have a direct outcome on the performance of their films.

Using data from various public movie databases, I will find patterns that speak to key factors in a movie's profitability and make recommendations based on my findings. These recommendations will better inform Microsoft's planning and increase the chances of success at the box office.

# Data Understanding

The available data consists of six databases available from various sources:

- IMDb
- Box Office Mojo
- Rotten Tomatoes
- The Movie Database (TMDb)
- The Numbers

All of these databases come from large and well-trusted film websites containing information on budgets, genres, runtimes, cast, and reviews. While certain tables may not contain the same movies as one another, most fit a general format, identifying movies with a unique ID that corresponds to subsequent information. Each table generally contains different information about a given film.

For this analysis, I will primarily be working with IMDb, The Numbers, and TMDb:

- IMDb's SQLite database covers a wide range of information that includes genre, runtime, cast, and reception
- The Numbers' database contains information on budgets as well as domestic and worldwide revenue
- TMDb's database includes detailed genre information based on genre IDs

# Methods

This project uses descriptive analysis of revenue and ROI trends over several factors: budget, genre, and runtime. This provides useful information about how to adequately balance a portfolio of movies to attain high revenues without sacrificing returns.

# Results

### Budget
<img src="adampell/Desktop/Budget_Chart_Final.png">

The relationship between budget and revenue is almost the opposite of the relationship between budget and ROI. As budget increases, revenue steadily increases as well. However, ROI declines as budgets increase. Despite a strong positive correlation between budget and revenue, it would seem optimal to avoid only making big-budget films as returns significantly diminish higher up the budget boards (save for a small group of exceptional outliers). 

### Genre
<img src="https://logos-world.net/wp-content/uploads/2020/09/Microsoft-Logo.png">
Adventure movies make the most gross revenue of any genre. Among the runners-up are Animation, Action, Family, and Science Fiction. Animation movies stand out, however, because their ROI is better than the other high earners. It is even more attractive because it can have elements of the other high-revenue genres.

### Runtime
<img src="https://logos-world.net/wp-content/uploads/2020/09/Microsoft-Logo.png">
Revenue tends to steadily increase with runtime, with the upside peaking around 140 minutes. Past that, it's unclear if a longer movie can sustainably make more money. Similar to with our budget analysis, though, ROI precipitously declines as runtime increases, then plateaus with a slight downward trend.

# Conclusions

This analysis led to three key business recommendations for Microsoft as they open their new studio:
- Produce ten films across multiple budget brackets, with a total studio budget of 650 million dollars.
- Focus resources on producing at least one animated film, with a secondary focus on action and adventure movies.
- Diversify runtimes, with higher-budget movies being longer than 113 minutes and lower-budget films being closer to 90 minutes.

My recommendations work together to form a coherent strategy: Using high-budget films to generate the bulk of the revenue and market the studio, while using low-budget films to generate high returns and appeal to niche audiences. This strategy properly diversifies Microsoft's film portfolio and balances risk while still being capable of producing high returns.

### Next Steps

Further analyses could yield other actionable insights for Microsoft. These include:
- Synergies between primary and secondary genre.
- Genre performance by runtime.
- Leading actor effect on revenue/ROI.
    
## Repository Structure
   
   - zippedData
   - .canvas
   - .gitignore
   - CONTRIBUTING.md
   - LICENSE.md
   - README.md
   - movie_data_erd.jpeg
   - student.ipynb

