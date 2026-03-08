## Movie Synopsis Clustering Study

This repository contains a Jupyter Notebook with a study on **text representation and preprocessing**, **dimensionality reduction**, and **clustering algorithms** applied to a movie dataset.

### Dataset

The dataset is organized in a `.csv` file with the following columns:

- **genres** – genres associated with the movie (a movie may belong to multiple genres)  
- **sinopse** – movie synopsis  
- **startYear** – release year  
- **primaryTitle** – movie title  
- **runtimeMinutes** – movie duration in minutes  
- **averageRating** – average movie rating  
- **numVotes** – number of ratings  
- **actors_names** – main actors/actresses  
- **directors_names** – movie directors  

### Objective

The goal of this study is to investigate whether there is a relationship between a movie’s **synopsis** and the **genre(s)** it belongs to.

To do this, movies are **clustered based on their synopses**, and then the **distribution of genres within each cluster** is analyzed. This allows us to evaluate whether movies grouped together tend to share similar genres or if different clusters exhibit distinct genre distributions.

### Methodology

The following steps were performed:

1. **Text preprocessing**
2. **TF-IDF matrix construction**
3. **Dimensionality reduction using Truncated SVD**
4. **Clustering using:**
   - K-Means  
   - Hierarchical Clustering  
   - Spectral Clustering  
5. **Methodology validation**
6. **Result interpretation**

The notebook explores how textual representations of movie synopses can reveal structural patterns related to film genres using **unsupervised learning techniques**.
