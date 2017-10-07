# Deep Learning Foundations Nanodegree
# Overview of projects

This is an overview of deep learning projects that I completed for the Udacity Deep Learning Nanodegree.

[//]: # (Image References)

[img_nn]: ./neural_net_numpy/img_nn.png "feed forward net"
[img_cnn]: ./cnn_images/img_cnn.png "cnn"
[img_rnn_tv]: ./rnn_tv_scripts/img_rnn_tv.png "rnn tv"
[img_rnn_translate]: ./rnn_seq2seq_translation/img_rnn_translate.png "translation"

[img_gan]: ./gan_faces/img_gan.png "gan faces"

### Install
These projects use Python 2 or 3 with TensorFlow 1.0 or higher.  See the individual README in each project folder for requirements.

## Feed Forward Neural Networks built in Numpy

![feed forward][img_nn]

- Built fully connected layers and implemented back propogation in numpy.  Used to predict bike share usage.

## Convolutional Neural Network for image classification

![cnn][img_cnn]

- Built a convolutional neural network and optimized with batch normalizaiton to reach 81.8% test accuracy.



## Recurent Neural Network for TV script generation

![rnn tv scripts][img_rnn_tv]

- Built a recurrent neural network to generate text that resembles tv scripts from the Simpsons TV show.

## RNN for Sentiment Analysis
- Built a recurrent neural network of multiple LSTM (long-short-term memory) cells.
- Used an embedding layer to convert words to vectors.
- Used GloVe (global vector of words) to set pre-trained word vectors in embedding layer.

## Seq2Seq RNN for language translation

![rnn translation][img_rnn_translate]
- Built a seq2seq recurrent neural network to translate text from English to French.

## Generative Adversarial Network for new image generation

![gan faces][img_gan]

- Built a generative adversarial network to generate new images that resemble human faces.  The discriminator learns to distinguish between real photos of faces and non-faces.  Concurrently, the generator network learns to generate data that the discriminator considers to be real faces.
