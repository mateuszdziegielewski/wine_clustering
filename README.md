# Clustering wine based on it's chemical characteristics

#### -- Project Status: Finished

## Project Intro
The analysis uses unsupervised machine learning algorythms to classify wines coming from different wineries into groups - each winery as one cluster. The only given varaibles are chemical qualities of every wine from the dataset.

Dataset file used in this project can be found [here](https://www.kaggle.com/datasets/harrywang/wine-dataset-for-clustering/data). The original data comes from [here](https://archive.ics.uci.edu/dataset/109/wine).

### Project organisation
<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>

### Methods Used
* Descriptive Statistics
* Data Visualization
* Machine Learning

### Technologies
* Python

See the [requirements](https://github.com/mateuszdziegielewski/wine_clustering/blob/main/requirements.txt).

## Project Description

Variables:
- Alcohol
- Malic acid
- Ash
- Alcalinity of ash  
- Magnesium
- Total phenols
- Flavanoids
- Nonflavanoid phenols
- Proanthocyanins
- Color intensity
- Hue
- OD280/OD315 of diluted wines
- Proline

Project includes exploratory data analysis and clustering algorythms. EDA shows the descriptive statistics of each varaible, as well as the correlation matrix and distributions displayed on boxplots. Clustering was done using Agglomerative Method (Ward's criterion) and K-means supported by different approaches to define the number of clusters. Those precisely were: dendrogram with the agglomeration distances plot and the elbow method. Results of the clustering were displayed in two and three dimensions using PCA (Principal Component Analysis) in order to cope with the multi-dimensionality of the data. For both clustering methods, Silhouette score was used to check their effectivnes.

### Featured Notebooks:
* [1.01-md-data_processing_and_EDA](https://github.com/mateuszdziegielewski/wine_clustering/blob/main/notebooks/1.01-md-data_processing_and_EDA.ipynb)
* [2.01-md-model](https://github.com/mateuszdziegielewski/wine_clustering/blob/main/notebooks/2.01-md-model.ipynb)

### License:
The dataset, as well as the project, are licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license, which allows for the sharing and adaptation of the datasets for any purpose, provided that the appropriate credit is given. For more details, check the [LICENSE](https://github.com/mateuszdziegielewski/wine_clustering/blob/main/LICENSE.txt).
