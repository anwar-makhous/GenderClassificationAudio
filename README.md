# GenderClassificationAudio

Prepared by: Anwar Makhous & Ahmad Shahla, Supervised by: Dr. Majd Ali, Prepared to obtain License in Computer and Automatic Control Engineering, Tishreen University 2020

# Abstract:

This project aims to create a classification system that can determine the gender of the
human speaker, by teaching a convolutional neural network (CNN) model and training it on a
data set consisted of audio data, after extracting the learnable features from that audio data
using the MFCC algorithm. We have explained some concepts within this documentation
related to the basics of signal and sound processing such as Fourier transform, DCT, and other
principles, which are necessary to understand the stages of the MFCC algorithm for extracting
features from audio clips. We also reviewed some concepts related to artificial intelligence,
artificial neural networks and the methodology of convolutional neural network, and we
reviewed some of the properties of the research tools we have used, including software and
data.
After searching for some neural network models, in similar studies, we adopted one of the
models for a convolutional neural network to achieve the system. We used two pre-prepared
data sets, the first one for training the network and the second one for testing the model. We
did some pre-processing operations on the audio signals, to extract the important information
from them. Then we extracted the features from the audio signals using the MFCC algorithm.
After that, we trained the network on the first dataset and determined the training accuracy,
and we tested the network on the second dataset and determined the accuracy of the test. We
also created our own data set. Then we also tested the network again to evaluate the model’s
performance in different conditions and its ability to generalize. We determined the accuracy
of the resulting test. Then we organized a table at the end of the fifth chapter to discuss the
results, and at the end of our research, we suggested some future developments.

# Training Dataset:
http://www.openslr.org/resources/45/ST-AEDS-20180100_1-OS.tgz

# Testing Dataset:
https://www.kaggle.com/liftofff9/voice-gender
