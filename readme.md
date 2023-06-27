# Overview

This is a dataset analysis project to familiarize myself with data analysis tools and techniques increasing my skillset in relation to these items.

The dataset analyzed is the [popular video games 1980-2023 dataset](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023). this dataset contains information about hundreds of popular games that have came out in the past 40 years including genres, reviews, ratings, player counts and other information.

[Software Demo Video](https://www.youtube.com/watch?v=1GhCMThHAU4)

# Data Analysis Results

For this analysis I asked three basic questions: 

* Firstly, how common is it for a studio to make multiple highly rated games? Is it a fluke or a pattern?

From my analysis of the data I have come to the conclusion that while some studios make games that are rated extremely highly more than once, it is not overly common. Looking at the first graph should in the notebook should reveal that the population of studios who have released an exceptionally well recieved game failed to do it more than a small amount of time and as such the graph is extremely weighted towards the left. While there are a few studios and publishers that have released many exceptionally well recieved games, that number is not high.

* Second, Do studios that consistently release good games, actually do better or is their consistensy of quality not enough for the average studio to achieve popularity?

The third graph shows analysis done on this. It shows the average rating of games that a studio makes and compares it to the average amount of people who have played that game. From it we see that there is a general upward trend in popularity as the games recieve better reviews. From this, I believe we can reasonably conclude that there is a general increase in popularity and success of games as they increase in quality. Oddly enough, this trend stops as games seem to hit the peaks of quality sharply decreasing in overall amount of people that have played them among the best reviewed games. There are a number of conclusions to be reached here, but I think that a reasonable conclusion from this is that the games that are technically the mosts impressive in what they offer also aren't neccesarily the things that usually appeal to the highest number of people nor do the studios that specialize in them reach the highest audience.

* The third question that I asked is whether the rating of a game actually determines its market viability. In general are highly rated games actually enjoyed and played more?

The second graph is constructed to answer this question. From it I have come to the conclusion that at least in average performance there is very little diffence between mid/low and highly rated games in terms of how many people actually played them. The general trend is pretty steady across the whole thing only being slightly higher in the lower 4 range compared to other areas. Lower ratings also seemed to do a little bit worse on average but it didn't seem like an enormous difference. Again like our last graph we see odd end behavior tho with the highest rated games actually being some of the least played further signifying in my mind that not only is the quality of a game not hugely indicitive of popularity but by creating many of the best rated video games, you actually end up limiting your audience.  

# Development Environment

This was developed in a jupyter notebook using Visual studio code. It uses the Pandas, altair, and ast library and was developed using Python. 

# Useful Websites

* [Altair example gallery](https://altair-viz.github.io/gallery/index.html#example-gallery)
* [Pandas Api Reference](https://pandas.pydata.org/docs/reference/index.html)
* [Popular video games dataset](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023)

# Future Work

* Clean up graphs and make them look visually cleaner
* Answer more data analysis questions