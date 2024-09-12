# Statistical Learning: Principal Component and Factor Analysis

This project focuses on understanding complex datasets using various statistical techniques such as Principal Component Analysis (PCA), Factor Analysis, and Clustering. The analysis was done as part of the Statistical Learning course at UC3M.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Visualization](#visualization)
- [Principal Component Analysis](#principal-component-analysis)
- [Factor Analysis](#factor-analysis)
- [Clustering](#clustering)
- [Conclusion](#conclusion)

## Introduction
This project was carried out for the Statistical Learning course at UC3M in November 2022. The main objective was to apply different statistical techniques to gain insights from a dataset, including PCA, Factor Analysis, and Clustering.

## Dataset
The dataset includes various attributes such as movie duration, Facebook likes (actors and directors), gross earnings, and IMDb scores. It was cleaned and prepared for analysis, including the elimination of duplicate records and the conversion of variables to the appropriate types.

## Data Preprocessing
- **Libraries used**:
  - `tidyverse`, `leaflet`, `rgdal`, `stringr`, `ggplot2`, `openxlsx`, `dplyr`, `factoextra`, `GGally`, `cluster`, `mice`, `mclust`, `kernlab`
  
- **Steps**:
  1. Remove duplicate movie titles.
  2. Convert variables such as duration, Facebook likes, and IMDb scores to numerical types.
  
- **Outlier Detection**: Boxplots were used to identify outliers, particularly in the `gross` variable, as this was considered a key indicator of a movie's success.

## Visualization
Several plots were generated to explore the dataset, including bar plots for various attributes like actor Facebook likes, gross earnings, and IMDb scores.

## Principal Component Analysis
PCA was performed to reduce the dimensionality of the dataset, allowing for better visualization and understanding of the underlying structure. Key components were plotted to assess their contribution to the overall variance.

## Factor Analysis
Factor Analysis was used to identify the latent variables influencing the dataset. This technique helps in reducing noise and better explaining the correlations between variables.

## Clustering
Clustering techniques like K-means were applied to group similar observations. The number of clusters was determined through various methods, and bar plots were used to visualize the centers of each cluster.

## Conclusion
The analysis revealed important insights, such as the significant contribution of variables like actor Facebook likes and gross earnings to the success of a movie. On the other hand, variables like the director's Facebook likes had a minimal effect.

## Installation
To run the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/statistical-learning-project.git
   cd statistical-learning-project
