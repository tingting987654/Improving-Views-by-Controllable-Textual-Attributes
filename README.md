# Improving-Views-by-Controllable-Textual-Attributes
Investigated the impact of controllable textual features (e.g., title, abstract, and document length) on article view counts while controlling for author, journal, and publication year effects.

# Analyzing Abstracts
The file journal data CW4.csv contains 4385 entries corresponding to papers published by the following journals between 2000 and 2022.

Journal of the Operational Research Society (https://www.tandfonline.com/journals/tjor20)

International Journal of Computer Mathematics (https://www.tandfonline.com/journals/gcom20)

Applied Artificial Intelligence (https://www.tandfonline.com/journals/uaai20)

Journal of Interdisciplinary Mathematics (https://www.tandfonline.com/journals/tjim20)

Each row corresponds to a published paper and contains the title, journal name, year, number of pages in the published version, a list of authors, the number of views of the paper on the website, the number of citations of the paper, an altmetric score and the abstract. The altmetric score provides a guide to the amount of attention a paper has received. See this
article for more details.

# Tasks
Objective in this assignment is to carry out some analysis on these data to look for interesting patterns and draw some general conclusions about the findings. Below we include tasks we worked through.

Bag of Words and TF-IDF: Carry out pre-processing of the abstract data to generate a corpus consisting of a set of documents each corresponding to a single abstract. Investigate the distribution of popular words in the corpus and draw plots to help the reader understand the findings. 

Topic modelling: Use LDA to search for different topics in the data and investigate how the topics vary between papers.

Classification and association: Using the data in the spreadsheet and results from previous sections, build classification models to determine how accurately it is possible to predict which journal a paper belongs to and association models to determine how often particular words appear together in different articles.

Clustering: Identify the clusters in the data using an appropriate clustering method. For each cluster, identify top words (e.g., by looking at the features with the highest mean TF-IDF scores in the cluster).

PCA: Visualise the clusters found in 2D by applying PCA to reduce the dimension.
