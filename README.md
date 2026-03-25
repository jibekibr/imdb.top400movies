# imdb.top400movies
Analysis of the IMDb Top 400 Movies dataset from Kaggle.

For the PHY 231 at Agnes Scott College, my teammates and I looked at IMDb Top 5000 Movies(only worked with Top 400) to answer the following questions:
  1. Does a movie’s length affect its rank/rating? Do longer movies tend to score better, or is shorter and tighter the way to go?
  2. Is there a relationship between the number of votes (popularity) and rating? Do "popular" movies actually rate higher, or do smaller films sometimes score better?
  3. What genre shows up the most? Has this changed over time?

We looked at the duration and rankings from audience and IMDb experts to answer the first question and examine the duration distribution. Here is our plot:
![averageratingvsduration.png]
!(My.plot)[Distribution of Movie Runtime.png]
Most films fall between 90 and 150 minutes, with a peak around 110–130 minutes, and we found no strong correlation, meaning that the movie length does not affect a movie’s rank.

For the second question, we used both ranking types and the number of votes, which together indicated the movie's popularity in our context. 
!(imagess)[Average rating vs amount of votes.png]
We observed a light positive correlation, meaning that more popular movies tend to rank higher.

Finally, the third question was answered by examining the overall distribution of genres and how the top 5 genres changed over time.
!(My.plot)[What is the most popular genres.png]
!(My.plot)[Top 5 Genres over time.png]
Looking at the graphs, one can see that the most popular genre changes over time. Action is currently most popular.
