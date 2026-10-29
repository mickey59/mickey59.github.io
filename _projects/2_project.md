---
layout: page
title: Song Recommender and genre classifier
description: Using applied machine learning techniques
img: assets/img/3.jpg
importance: 2
category: work
giscus_comments: false
---

One project I was apart of was tasked with Spotify's Top 200 playlists dataset from January 2017 to May 2023. We were tasked to extract the most useful information out of this data and provide some interesting insights to hypothetical users.

We settled on creating a song recommender and genre classifier. We first worked on cleaning the data and dropping features that weren't relevant significantly reducing the bloating of the data itself. We settled on genre super-classes to help cluster the given songs into broader categories. We also enriched the dataset by extracting the language being sung among other things.

We then implmented multiple different models to learn and train the models on what features in the data corresponded with each genre. 

We also created a song recommender, we did this by using a core feature of the songs; the lyrics. By using semantic embeddings of the song data and used multiple metrics to learn which songs are similar. 

The repo can be found [here](https://github.com/mickey59/AML_Spotify)

