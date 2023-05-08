# Spotify - Recommender System


## Intro
Our project focused on a recommendation system for Spotify songs.  
There are many ways to achieve this, like euclidean distance from vectors created by lyrics. Or by clustering the similarities of musical features of the songs. Which we have chosen the latter.  

The dataset is updated until 2020, so no newer songs will be available. Although it is considered in future work.  

Recommendation systems are widely used in Social media, Streaming services, E-commerce, News websites, Travel websites,Job search websites. So, getting used to this projects, will be an advantage postulating to those kind of jobs  

## Observations
Some songs have 0 on tempo* (On first sight, The songs without tempo are: either too old that were not correctly registered, OR white-noise songs (i.e. rain noise), which are same frequency along the song. hence, there is no tempo on it.)

Results could be improved if we had "language" feature to train our model.   

We have received recommendations for songs that sound similar, but on different languages.   

An example is "Basket Case by Green Day" the model suggests "O Saathi Re - Female Vocals by Asha Bhosle, Kishore Kumar"  

## Future work
Creation of GUI to easier usage  

Autofill songs, to avoid misunderstanding  

Update database using spotipy  

pip install scikit-surprise  