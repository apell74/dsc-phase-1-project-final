<img src="https://logos-world.net/wp-content/uploads/2020/09/Microsoft-Logo.png" alt="Microsoft Logo" width="400" align='left'>

# Microsoft Movie Studios- Industry Analysis

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

Image: IMDb SQLite Database Schema

# Methods

This project uses descriptive analysis of revenue and ROI trends over several factors: budget, genre, and runtime. This provides useful information about how to adequately balance a portfolio of movies to attain high revenues without sacrificing returns.

# Results

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
    


