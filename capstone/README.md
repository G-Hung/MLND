# MLND
Udacity machine learning nanodegree
capstone project

*Special thanks to Google Cloud Platform, their generous 300USD free-trial makes this project possible by using GPU.*

Data:
The original data is from Kaggle tensorflow audio completeion, since I used only subset and do train-valid-test split, please refer to the data in this google storage bucket. Data size is around 500MB

links:
https://storage.googleapis.com/kaggle_ghung/tensorflow_audio/udacity/audio_test.zip
https://storage.googleapis.com/kaggle_ghung/tensorflow_audio/udacity/audio_train.zip
https://storage.googleapis.com/kaggle_ghung/tensorflow_audio/udacity/audio_valid.zip

Suggested folder structure:

root -- data     -- train
    |            -- valid
    |            -- test
     -- notebook -- data-exploration.ipython
    |            -- model-exploration-revised.ipython
     -- model
    |
     -- result


Package:
Needed packages are listed in ipython notebook import sessions
special note: keras, I use 2.1.2 due to I can't load h5py in datalab if I use the latest version
