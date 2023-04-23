# Anime-Score-Prediction-SC1015-mini-project
<img width="659" alt="image" src="https://user-images.githubusercontent.com/92656053/233773727-2299fd9e-a5bb-4fac-9e99-e2c0e2fb3521.png">

## About

This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on anime from [MyAnimeList API dataset](https://myanimelist.net/blog.php?eid=835707). 

Cleaned Dataset used: 
1. anime_details_cleaned+genres.csv
2. anime_details_cleaned
3. tree.dot
4. tree.png

For a detailed walkthrough, please view the source code in order from:

1. [Data Preparation & Cleaning](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/f36a31005ee0257ea072e69145b5554ec99bb4b1/Data%20Preparation%20&%20Cleaning.ipynb)
2. [Exploratory Data Analysis & Visualization](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/942a58f16c219fe2fe9f3a187b2bba4faa844e42/Exploratory%20Data%20Analysis%20&%20Visualization.ipynb)
3. [Regressions](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/812b0ad3d0ca06a0b0bc5db248ef2b6063b26b34/Regressions.ipynb)
4. [Machine Learning - Classification](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/c130583d2afb76dc9837841502723c156c10982e/Machine%20Learning%20-%20Classification.ipynb)
5. [Machine Learing - Clustering](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/515b305e7ab9f803289513868d7dd7d5649a5c6e/Machine%20Learning%20-%20Clustering.ipynb)
  
## Contributors

- @kevinpxq - Data Preparation & Cleaning, Exploratory Data Analysis & Visualization, Machine Learing - Clustering
- @JYL480 - Exploratory Data Analysis & Visualization, Linear Regressions
- @YuQuanang - Machine Learning - Classification, Exploratory Data Analysis & Visualization

## Problem Definition

- How can we help viewers discover new and enjoyable anime series?
- Which model would be the best to predict it?

## Models Used

1. Regression - Linear, Polynomial and Ridge 
2. Classification tree and Random forest
3. Clustering - Kmeans clustering

## Conclusion

- Random forest and polynomial regression are the better models to use compared to the other models in classification and regression respectively
- Watch rate, start season year, rating, and start season year, season and popularity are important factors in finding which anime is of good quality and enjoyable to the viewer
- Kmeans allowed us to understand that genre, media type and source material are the 3 other factors that allowed us to identify a good quality anime
- Some of the Machine Learning models such as classification have certain flaws that may cause its results to hold less weight

## Similarities of a good anime (Detailed findings)
- Created between 2020 and 2022
- R rated anime 
- Anime presented in the form of a movie
- Anime story is adapted from mangas
- Genre of anime: Adventure or Drama


## What did we learn from this project?

- Handling raw datasets by cleaning and
- Using of Kmeans Clustering and silhouette score
- Polynomial and Ridge Regression 
- API Usage
- Learn to open JSON array to form useful information
- Using of GraphViz to display tree table
- Conversion of .dot file to .png file
- Collaborating using GitHub

## Slides Link
[Google Slides presentation](https://github.com/YuQuanang/Anime-Score-Prediction-SC1015-mini-project-/blob/f2ed102a38e6bf9c17daf0890994e9eb982ad765/SC1015%20-%20MiniProject%20(1).pdf)

## References
1) <https://towardsdatascience.com/how-to-visualize-a-decision-tree-from-a-random-forest-in-python-using-scikit-learn-38ad2d75f21c>
2) <https://www.datacamp.com/tutorial/random-forests-classifier-python?utm_adgroupid=143216588577&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=655068781125&utm_targetid=dsa-1947282172981&utm_loc_interest_ms=&utm_loc_physical_ms=9062538>
3) <https://www.upgrad.com/blog/types-of-regression-models-in-machine-learning/>
4) <https://www.datacamp.com/tutorial/k-means-clustering-python?utm_source=google&utm_medium=paid_search&utm_campaignid=19589720821&utm_adgroupid=143216588577&utm_device=c&utm_keyword=&utm_matchtype=&utm_network=g&utm_adpostion=&utm_creative=655068781125&utm_targetid=aud-299261629574:dsa-1947282172981&utm_loc_interest_ms=&utm_loc_physical_ms=9062512&utm_content=dsa~page~community-tuto&utm_campaign=230119_1-sea~dsa~tutorials_2-b2c_3-row-p1_4-prc_5-na_6-na_7-le_8-pdsh-go_9-na_10-na_11-na-aprfs23&gclid=CjwKCAjw6IiiBhAOEiwALNqncf6iG3FNrLjx7DuSn607fX2O5idGXoWWaDMi_Tp-0BIgmOYNU7WcdBoC6V8QAvD_BwE>
