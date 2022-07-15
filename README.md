# Netflix-Movies-And-TV-Shows-Clustering

## Problem Statement

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Flixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

![image](https://user-images.githubusercontent.com/85817763/179209147-2f8e46de-375f-4a60-8d77-460cdbce229d.png)

Attribute information:
 
1. show_id : Unique ID for every Movie / Tv Show

2. type : Identifier - A Movie or TV Show

3. title : Title of the Movie / Tv Show

4. director : Director of the Movie

5. cast : Actors involved in the movie / show

6. country : Country where the movie / show was produced

7. date_added : Date it was added on Netflix

8. release_year : Actual Releaseyear of the movie / show

9. rating : TV Rating of the movie / show

10. duration : Total Duration - in minutes or number of seasons

11. listed_in : Genre

12. description: The Summary description

The main objective here is to explore and analyze the data to extract some fruitful insights from it and to cluster similar content, based on text based clusters which further helps in generating recommendations.

## Project Approach 

Netflix is the world’s leading premium media streaming platform, operating in nearly every country in the world. It is one of the first players in the streaming industry and the bet has paid off with hundreds of millions of subscribers worldwide. It has even led people using phrases like "binge watching" and "Netflix and chill". 
Following are the steps being taken during the analysis process:
* Got hands on the data in order to check it's nature and found out to be non-labeled dataset which clearly stated that it was problem statement need to be solved     using unsupervised machine learning algorithms. 
* Inspected the dataset and found a bunch of missing and null values.
* Cleaned and pre-processed the dataset using necessary techniques so as to make the dataset ready to be used in training machine learning models.
* Carried out some exploratory data analsyis using different visualisation techniques.
* Performed tokenization, vectorization and removed stopwords in order to perform text cleaning.
* Used elbow method and silhouette scoring method to find out optimal value of 'K' which is used for K-means clustering algorithm.
* Performed principal component analysis (PCA) so as to get rid of curse of dimensionality.
* At the end created a recommendation system using cosine similarity.

# Conclusions

1.   **There are basically two types of content in the dataset: 'Movies' & 'TV shows'.**
2.   **Netflix has more movies which constitutes 69.05% of total content than TV shows which is only 30.95% of total content.**
3.   **'Christmas', 'Love', 'Man', 'World' are some of the most utilized words for movie titles.**
4.   **'Raul Campos and Jan Suter' have most number of contents in this particular dataset.**
5.   **'United States' tops the list with maximum number of contents.**
6.   **Most of the movies are 'TV-MA' rated.**
7.   **Most of the TV shows are 'TV-MA' rated as well.**
8.   **Most movies were released during the last decade (2010 - 2020 ) compared to all other time periods.**
9.   **Most of the movies were released in the year 2017 followed by 2018 and 2016.**
10.  **Most of the TV Shows were released in 2020 followed by 2019 and 2018.**
11.  **Majority of the movies have duration ranging from 85 minutes to 120 minutes.**
12.  **'Family', 'life', 'find', 'friend' are some of the most utilized words in description.**
13.  **Most of the streamed TV Shows have only one season.**
14.  **Most of the contents are basically documentaries.**
15.  **Optimal number of clusters were found out to be 27 with silhouette coefficient value of 0.02765.**
16.  **Principal component analysis was performed in order to reduce the dimensionality which improved the silhouette coefficient to 0.3561.**

