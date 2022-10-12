# Spotify-Valence-Prediction

Spotify uses a metric called valence to measure the happiness of a track. The metric itself, however, was not developed by Spotify.
It was originally developed by Echo Nest, a company that was bought by Spotify in 2014. We don't know exactly how valence is calculated.
Some details are given by a blog post, which you can find here:

https://web.archive.org/web/20170422195736/http://blog.echonest.com/post/66097438564/plotting-musics-emotional-valence-1950-2013

The project's task is to untangle the mystery behind valence and propose how this is derived.

Spotify offers the following information that have been releveant to the task:

Get Track's Audio Features and Get Tracks' Audio Features.

Get Track's Audio Analysis.

There are two main goals on this project.
Goal #1: To explore which features influence the Valence: By using inferential statistic methods to study how features (track and possibly audio) influence valence.
I am trying to find the best possible model for explaining the valence based on the features that you find significant.

Goal #2: Predict Valence: By using Machine Learning techniques to predict valence based on track features.
There are both neural network and non-neural network techniques used on this project. This happened of course in order to explore ore techniques and expand my skillset,
but at the same time to understand the power of the NNs.
