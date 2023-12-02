### PROJECT TITLE: "Data Analytics on IMDB TOP1000 dataset"

#### DEMO VIDEO: 
https://youtu.be/wE-iiLU2B0U

#### DESCRIPTION:
The project goal is to do some data analytics and visualization on **"IMDB (Image Movies Data Base) TOP 1000 Movies"** dataset. 

The language used is Python, including state of the art libraries such as *"pandas"*, *"matplotlib"*, *"seaborn"*, *"wordcloud"*, "nltk"*. The IDE used is *Jupyter Lab*.

The dataset was provided in form of CSV and was transformed and manipulated using pandas library.

The useful information that I've managed to extract and visualize was:
* The most successful year in movie industry
* The most successful main actor
* The most successful secondary actor
* The most successful director
* The most common words in movies "Overview"
* The most common movie genres
* Dependencies between IMDB_Rating, Meta_Score & No_of_Votes

<u>bonus</u>: 
* Sentiment analysis on "Movie Overview" section

Used different visualization types such as bar charts, heat maps and word clouds.

Also, performed sentiment analysis on a DataFrame column containing movie overviews using the Natural Language Toolkit (NLTK) library. The goal is to categorize the sentiment of each movie overview into positive, neutral, or negative, and visualize the distribution of sentiment categories.

Steps:
Data Preparation:

Import necessary libraries, including NLTK, pandas, seaborn, and matplotlib.
Create or load a DataFrame with movie information, including titles and overviews.
Sentiment Analysis:

Initialize the Sentiment Intensity Analyzer from NLTK.
Apply sentiment analysis to the 'Overview' column using the analyzer to calculate compound sentiment scores.
Categorizing Sentiment:

Map sentiment scores to categories (Positive, Neutral, Negative).
Define conditions based on sentiment scores.
Create a function to categorize sentiment and apply it to create a new column ('Sentiment_Category').
Visualization:

Create a bar plot using seaborn to visualize the distribution of sentiment categories.
The plot provides insights into the overall sentiment distribution of the movie overviews.
#### DATASET SOURCE:
https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows

