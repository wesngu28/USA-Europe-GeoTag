# A Comparison of Geo-Tagged Tweets from the United States and Western Europe
In this repository, I use Twitter's API and the Tweepy library for python to analyze geo-tagged tweets from the United States and Western Europe (from Iberia to Sweden), and visualize the data using word clouds. The purpose of this is to analzye the geographic distribution of these tweets in their respective regions and notice any noticeable trends and differences.

I chose these two particular regions because these regions tend to make up what we traditionally know as the Western World, and I wanted to observe any noticeable cultural trends or general patterns that may come up between them.

## Map 1: United States
![USA Tweet Map](https://user-images.githubusercontent.com/60171023/164874944-26b0eadb-6472-4941-abc6-71b29ef41067.png)
This first map is just a map of the distribution of tweets across the United States, as well as the Vancouver and Toronto metropolitan areas and some parts of Northern Mexico.

## Map 2: Western Europe
![Europe Tweets](https://user-images.githubusercontent.com/60171023/164875031-7ac1ed33-1d9f-41d9-a934-6e516e1a085b.png)
This second map is a map of the tweet distribution in Western Europe. Due to the inexactness of the Tweepy location object, it includes some tweets from Slovakia and Sarajevo, regions that are not included in Western Europe. I made the decision to include Norway and Sweden as they tend to be lumped in with the Western World.

### Observations
To start, the map of the United States's distribution tends to match the general population map of the country. The East Coast dominates the general distribution, with the majority of tweets appearing along the Eastern Seaboard and the eastern half of the country in general. The main source of tweets along the West Coast is in California, the most populous state in the union. Besides this, the tweet map is almost entirely dominated by urban and metropolitan regions. Of the over 3,000 tweets that were streamed, it seems that a very small number came from rural regions and small towns.

In the European map, it is hard to not notice that the distribution is dominated by the United Kingdom. This is pretty obvious because the filter searched for English tweets, and the British Isles is the only place in Europe where English is the primary and native language. However, the distribution also includes other parts of Europe, and this is because European countries have a lot of emphasis on teaching English, as well as pressure to learn English due to the influence of American culture.

The United States have almost 5x more tweets logged than the map of Western Europe, despite the two regions having about equal populations. One reason why this might be the case is again the filtering for the English language, as other countries besides Ireland and the UK would most likely be dominated by tweets in their native language. French users may be using their own social media platform that is catered towards French speakers, or simply just be tweeting in French. Also, the time that I ran the script was 7 PM PST, which is around 4 AM in Europe, and this would definitely play into the amount of tweets from the region as a whole.

## Word Cloud of the United States
![USA Word Cloud](https://user-images.githubusercontent.com/60171023/164876518-607d37b7-8315-45b0-af20-40a3d4f3756b.png)

## Word Cloud of Western Europe
![Western Europe Word Cloud](https://user-images.githubusercontent.com/60171023/164876544-afffa58d-3ac8-4ffa-b6f1-f270a306182c.png)

The problem with these word clouds is that because there was no specific key word searched for, a lot of these tweets are personal tweets about where people are going or just how people are feeling. This is evident in the word map of the United States, as go, out,and love are some of the most common words. This also seems to be the case for Europe, although their most common word is follow, which probably correlates with the general time, as I would expect most normal users to be sleeping and a more active number of bots to real people. 

Besides that, the main thing that I noticed with the Western Europe word map is that some of the most common words clearly have a sexual connotation.
