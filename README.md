# Music generation using deep learning
Generating music using deep learning

## Real World problem
This case-study focuses on generating music automatically using Recurrent Neural Network(RNN). We do not necessarily have to be a music expert in order to generate music. Even a non expert can generate a decent quality music using RNN. We all like to listen interesting music and if there is some way to generate music automatically, particularly decent quality music then it's a big leap in the world of music industry. Task: Our task here is to take some existing music data then train a model using this existing data. The model has to learn the patterns in music that we humans enjoy. Once it learns this, the model should be able to generate new_ music for us. It cannot simply copy-paste from the training data. It has to understand the patterns of music to generate new music. We here are not expecting our model to generate new music which is of professional quality, but we want it to generate a decent quality music which should be melodious and good to hear. Now, what is music? In short music is nothing but a sequence of musical notes. Our input to the model is a sequence of musical events/notes. Our output will be new sequence of musical events/notes. In this case-study we have limited our self to single instrument music as this is our first cut model. In future, we will extend this to multiple instrument music.

## Type of Data:
There are total of 405 music tunes in abc notation.

## Prerequisites
You need to have installed following softwares and libraries in your machine before running this project.

Python 3
libraries which are needed like sklearn, pandas, seaborn, matplotlib, numpy, scipy.
keras

## Reference
https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
http://karpathy.github.io/2015/05/21/rnn-effectiveness/

