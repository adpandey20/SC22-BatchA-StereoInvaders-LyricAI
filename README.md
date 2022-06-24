# Read Me
## About the Team

When first starting all of us had some coding experience but none of us had any real knowledge of AI or python. Yet through the weeks, we were able to learn, and even when we were down to 4 people in a zoom call we worked through it and scraped our whole project together.


## How to Use

Enter a prompt and move the slider to get the desired craziness/randomness of the lyrics and then choose your emotion and click submit to get the lyrics!

## Dataset

Multiple datasets were used to train our AI. We started with a dataset that contained the emotions of sadness, tenderness, and tension. We used it because it contained both lyrics and emotions which every other dataset we looked at lacked. Either they would have lyrics and no emotions or emotions and no lyrics. But we were able to train the AI on those models in a day so we tried to do more. We used the Muse dataset from Kaggle which is a huge list of songs that contains emotions for those songs. Then we used the Genius API and python to generate a dataset that would pull the lyrics from the Genius API and add them to the corresponding songs.

## Tech Stack

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## The Model
We used the GPT-neo model which is an unsupervised learning algorithim with 125 million paramters. We trained a new model for each emotion. 


## Libraries Used

In python the libraries we used were pandas to get the data prepared, lyricsgenius to get the lyrics from the genius API, and aitextgen to train our models.
