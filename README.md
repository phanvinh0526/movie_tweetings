# Movie Tweeting Analysis

Movie Tweetings is an analysis on Movie Tweeting data [1]. This analysis can give an initial movie recommendation for **Cold start visitors** who access the website in the first time. Since new visitors registers to the system and requests recommendations before providing any rating. Popular movies are very likely to be interesting to the majority of users and hence to serve them the initial stage of their interaction with a recommender system.

## Installation

Use the RStudio [rstudio](https://rstudio.com/products/rstudio/download/) to open R Markdown file *(./notebooks/movie_popularity_analysis.Rmd)*.

Online version: [Demo](https://phanvinh0526.shinyapps.io/movie_popularity_analysis/)

## Libraries
R libraries (shiny, readr, dplyr, lubridate, stringr)

## Further
Python script to implement Novel modified SVD (singular value decomposition) is under-construction. SVD can help to find similarity among movies based on exponent characterising factors, which was conducted in [2]


## Reference
[1] [Movie Tweetings dataset](https://github.com/momenton/momenton-code-test-movietweetings/tree/master/snapshots/100K)

[2] Kumar, R., Verma, B. K., & Rastogi, S. S. (2014). Social Popularity based SVD Recommender System. International Journal of Computer Applications, 87(14), 33–37. doi: 10.5120/15279-4033
