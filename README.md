# Xbox Series X Games Clustering Project

### Collaborators: 

- [Chrys Voutselas ](https://github.com/cvoutselas)
- [Felix Wilfried ](https://github.com/Felix-W-F)

Welcome to the Xbox Series X Games Clustering Project! In this project, we aim to explore and analyze Xbox Series X games by applying unsupervised learning techniques to group them based on their descriptions. We utilize the TfidfVectorizer to transform the textual data into numerical feature vectors, and then employ the K-means clustering algorithm to identify distinct clusters among the games. To visualize the clusters effectively, we use Principal Component Analysis (PCA) for dimensionality reduction.

## Dataset

The dataset used in this project is obtained by scraping data from the Metacritic website. Metacritic is a popular review aggregation platform that provides ratings and descriptions for video games. Using the BeautifulSoup library, we extract relevant information about Xbox Series X games, such as the game's title, release date, Metascore, and the textual description or review. The descriptions are crucial for our clustering task as they capture the essence and content of each game.

The web scraping process ensures that our dataset includes the latest and most up-to-date information on Xbox Series X games available on Metacritic. By gathering this data programmatically, we can analyze a diverse range of games, covering different genres, themes, and styles.

## Notebook

The complete code, along with detailed analysis, can be found in our Jupyter Notebook [here ](https://github.com/felipegomez30/games-clustering-project/blob/main/notebook/videogames-project.ipynb). In the notebook, you will find step-by-step explanations of the data collection, data preprocessing, TfidfVectorizer implementation, K-means clustering, PCA visualization, and the evaluation of the clustering results.

## Results

![download (2)](https://github.com/felipegomez30/games-clustering-project/assets/130583163/28343aaa-2316-4c03-81bd-5adfe30098dd)

![download (3)](https://github.com/felipegomez30/games-clustering-project/assets/130583163/769c8686-7a2a-4121-ac6b-d7a8334b4491)

After applying K-means clustering with TfidfVectorizer, we explore different numbers of clusters to determine the ideal groupings for the Xbox Series X games. By analyzing Within-Cluster Sum of Squares (WCSS) and Silhouette Score, we identify that the optimal number of clusters is 2. The PCA visualization helps us visualize the clusters' separation, confirming that the clustering is more effective than random assignment. This meaningful partitioning of games enables us to identify distinct groups of Xbox Series X games based on their textual descriptions, potentially revealing patterns and similarities among different game titles.

![download (1)](https://github.com/felipegomez30/games-clustering-project/assets/130583163/7ecf59ba-c9ef-4cf6-b415-5826036558da)

## Conclusion

We hope this project provides insights into the Xbox Series X gaming landscape and inspires further research and exploration of clustering techniques in the gaming domain.

Note: Due credit is given to the Metacritic website for providing the data and BeautifulSoup library for its role in web scraping.
