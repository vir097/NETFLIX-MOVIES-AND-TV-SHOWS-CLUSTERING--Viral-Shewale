# NETFLIX-MOVIES-AND-TV-SHOWS-CLUSTERING

## Abstract:-
* Although OTT platform such as Netflix is a recent phenomenon, rapid growth has made it a leading competitor in the streaming media and production firm.
Netflix subscriber count as of 2022 is 220.67 million. 
* It is crucial that they effectively cluster the shows that are hosted on their platform in order to enhance use experience.

## Problem statment:
* In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.

**In this project, we are required to do**
* Understanding what type content is available in different countries.
* Is Netflix has increasingly focusing on TV rather than movies in recent years.
* Clustering similar content by matching text-based features.

## Data Pre-Processing:

1. Select the attributes based on which you want to cluster the shows.

2. Text preprocessing: Remove all non-ascii characters, stopwords and punctuation marks, convert all textual data to lowercase.

3. Lemmatization to generate a meaningful word out of corpus of words.

4. Tokenization of corpus.

5. Word vectorization.

6. Dimensionality reduction.

7. Use different algorithms to cluster the movies, obtain the optimal number of clusters using different techniques.

**We will cluster the shows on Netflix based on the following attributes:**

* Director
* Cast
* Country
* Listed in (genres)
* Description


## Conclusion:

* In this project, I worked on a text clustering problem wherein I had to classify/group the Netflix shows into different clusters where each data point belongs to only one group.

* The dataset contained 7787 records and 11 attributes.

* I started by dealing with missing values ​​of datasets and doing exploratory data analysis (EDA).

* Netflix hosts more movies than TV shows on its platform, and the total number of shows added on Netflix is growing exponentially.

* United state produces the highest number of shows.

* Cluster the data based on the attributes: director, cast, country, genre, and description. The values in these attributes were tokenized, preprocessed, and then vectorized using the TFIDF vectorizer.Through TFIDF Vectorization, I created a total of 20000 attributes.

* I used principal component analysis to reduce the dimensionality of the data. 84.57% of the variance is explained only by 4000 components, so the number of the components was restricted to 4000.

* The Elbow method and Silhouette score were used to decide the optimal number of clusters for the K-means clustering algorithm, and the obtained number of the Clusters was 5 (k=5), and then the K-Means clustering was built.

* Then clusters were created using the agglomerative clustering algorithm, and the optimal number of Clusters turned out to be 12 after looking at the dendrogram.
