# TMDB-project
## Overview
The TMDb Movies Dataset contains information about movies collected from The Movie Database (TMDb). It includes details such as budget, revenue, cast, director, popularity, and more, making it useful for analyzing trends in the film industry.

## Dataset Overview
The dataset consists of 10,866 movies with 21 attributes. Below are the key columns:

id: Unique identifier for the movie.
imdb_id: IMDb identifier.
popularity: Popularity score.
budget: Production budget (in USD).
revenue: Total revenue (in USD).
original_title: Movie's original title.
cast: List of main actors.
homepage: Official website (if available).
director: Movie director.
tagline: Promotional tagline.
keywords: Keywords associated with the movie.
overview: Short movie summary.
runtime: Duration (in minutes).
genres: Movie genres (e.g., Action, Comedy).
production_companies: Production companies.
release_date: Release date.
vote_count: Number of votes.
vote_average: Average rating.
release_year: Year of release.
budget_adj: Budget adjusted for inflation.
revenue_adj: Revenue adjusted for inflation.

## Conclusion:
1. High cost does not insure the highest Financial return.
2. The dataset contains null values and outliers all been dropped. 
3. There is a weak positive coloration between movie time Financial return.
4. Dataset size reduced from 1.7+ MB to 1.2+ MB.
5. The duplication can't be taken as indicator because the data can overlap due to similarity in naming.
6. The study used the histogram to understand the distribution of the data to apply early detection of outliers and the heat map to understand the coloration.
7. The shape changed from _(10866, 21)_ to _(9882, 21)_
