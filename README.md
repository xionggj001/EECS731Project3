# EECS731Project3

# Data interpretation


We use the MovieLens 20M Dataset

It contains 20 million ratings and 465,000 tag applications applied to 27,000 movies by 138,000 users. Includes tag genome data with 12 million relevance scores across 1,100 tags. Released 4/2015; updated 10/2016 to update links.csv and add tag genome data.

# Data sets included

Ratings Data File Structure (ratings.csv)
Tags Data File Structure (tags.csv)
Movies Data File Structure (movies.csv)

# Part 1: Data Exploration

First of all, we clean the data sets, and analyze the three data sets. We characterized the data statisitics and generate several visulizations to demonstrate the data value of these data sets. 

We analyze the tags and genres of each movie. Each genre contains how many movies has be visulized and the distribution of each genre has also been charterized.  


# Part 2: Clustering for Movie Recommendation

In this part, we adopt the K-nearest model for the  clustering task. We first transform the genre and tags data into one-hot vector and add them into the dataframe. We also leverage the statistic information of ratings. As we can see from the clustering results, the recommendation system actually recommends the movies within similar years. This might happend due to the similar types of movies within similar years. 
