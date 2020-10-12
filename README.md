# Mini Project

## Classify Song Genres from Audio Data



[![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)](https://www.google.com/does_not_exist.jpg%20404)
[![WIP](https://img.shields.io/badge/repo%20status-WIP-yellow)](https://www.google.com/does_not_exist.jpg%20404)


## Project Description
Using a dataset comprised of songs of two music genres (Hip-Hop and Rock) which are based entirely on track information derived from Echonest (now part of Spotify) a classifier is trained in order to distinguish between this two genres. 

First data exploration and visualization is carried out using ```pandas``` and ```seaborn``` packages to find obvious trends and patterns in the data.

Next predictions are made using ```scikit-learn``` package to predict whether it is possible to correctly classify a song's genre based on its features(danceability, energy, acousticness, tempo, etc).

Some common algorithms such as PCA, logistic regression, decision trees will then be implemented.

This project deals with Supervised Machine Learning, which involves data preprocessing, dimensionality reduction, and machine learning using the scikit-learn package.

## Datasets
* ```echonest-metrics.json```   - 

dataset that has musical features of each track such as danceability and acousticness on a scale from -1 to 1.
* ```fma-rock-vs-hiphop.csv```  - 

song track details such as bit_rate, comments, composer, date_created, date_recorded

## Purpose of the Task

Over the past few years, streaming services with huge catalogs have become the primary means through which most people listen to their favorite music. But at the same time, the sheer amount of music on offer can mean users might be a bit overwhelmed when trying to look for newer music that suits their tastes.


For this reason, streaming services have looked into means of categorizing music to allow for personalized recommendations. One method involves direct analysis of the raw audio information in a given song, scoring the raw data on a variety of metrics. This task will be examining data compiled by a research group known as The Echo Nest. The goal is to look through this dataset and classify songs as being either 'Hip-Hop' or 'Rock' - all without listening to a single one ourselves. In doing so, we will learn how to clean our data, do some exploratory data visualization, and use feature reduction towards the goal of feeding our data through some simple machine learning algorithms, such as decision trees and logistic regression.