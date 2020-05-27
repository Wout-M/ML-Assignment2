# ML Assignment 2
This repo contains the dataset and jupyter notebook for Assignment 2 for DAT 158 Machine Learning and Advanced Algorithms. We will try to predict the valence, or happiness, of a song.

## Dataset
A dataset containing 232 725 songs from 26 different genres. Downloaded from [here](https://www.kaggle.com/zaheenhamidani/ultimate-spotify-tracks-db/).
Features:
* Genre
* Artist name
* Track name
* Track id
* Popularity 
* Acousticness
* Danceability
* Duration (ms)
* Instrumentalness
* Key
* Liveness
* Loudness
* Mode
* Speechiness
* Tempo
* Time signature
* Valence

More info about these features can be found [here](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-features/)

## Notebook
In the notebook we first explored the data to gain insights. Then we processed the data to prepare for model training using a few custom pipelines. Next we tried some different models and finetunde said models. After that we combined a few models with stacking/blending for possibly even better performance. Lastly, we predicted on the test set with all the best models and compared their performance.