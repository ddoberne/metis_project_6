# Using Deep Learning to Track Genre Trends in the Music Industry
## Background

The music industry is, well, <ins>the</ins> music industry, with billions of dollars of revenue per year in the US alone. In order to cater to its audience, music is labeled as being part of a genre such as Pop, Jazz, R&B, Country, Latin, etc. The issue with these classifications is that they are essentially moving targets; what defines a genre in a certain year is prone to change in subsequent years. An example of this is the Michael Jackson hit "Billie Jean", which won a Grammy as an R&B song. Fortunately, these trends are often cyclical and involve movement toward and away from other existing genres. Is this movement predictable? This project aims to break down songs into components of genres using data science, and see if there are any trends that could be insightful.

## Design

This project will use the GTZAN data set for audio, which consists of 100 audio samples of 10 different music genres, for a total of 1000 examples. The project's scope will be twofold:
1. Train a neural network to read in data from the audio files and classify a song's genre
2. Take award-winning songs from the last decade and see how the model classifies them, using soft classification to see if any trends arise.

## MVP
The MVP for this project will be to have a working neural network that can classify an input song into one of the ten genres.
