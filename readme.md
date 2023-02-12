## Inspiration
Keeping up with new information on COVID-19 can be a challenge for health professionals due to the vast number of literature and rapid spread of the virus. Is it possible to simplify the search for related publications by clustering similar research articles together? In what ways can the cluster content be qualified?
## What it does
With the use of clustering for labeling and dimensionality reduction for visualization, the collection of literature can be represented by a scatter plot. On this plot, publications of highly similar topics will share a label and will be plotted near each other. In order, to find meaning in the clusters, topic modeling will be performed to find the keywords of each cluster.
## How we built it
We used Kaggle for datasets and notebook. We used sentence transformer and UMAP along with K Means for clustering. We also used BERTopic for topic modeling and visualisation
## Challenges we ran into
Some of the challenges we are into
* The number of Dataset was huge and was not able to process the whole dataset
* A number of entries in  datasets were not in english
* A lot of stopwords and some words were very common in the articles
## Accomplishments that we're proud of
We are accomplished of using more advanced technologies
## What we learned
We learned data preprocessing in NLP and how to use BERTopic for topic modeling
## What's next for SCLUVID
Next SCLUVID is to deploy a web based app 