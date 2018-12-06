# Machine Learning Engineer Nanodegree
## Capstone Proposal
Mahmoud Hamdy Fahmy 
4/12/2018
## Using Deeplearning convert `Speech` to `text`
## Domain Background 
- It one of my primary areas of focus , and Udacity is one reaseon that give me the idea to work in `speech recognation` , it also talk about 
`speech recognation` which is a cretical area we need to see it , mean we need to change signals of speech to words, this is really cretical , I decide to work 
in this area because of I need to get more in working with speech and deeplearning ( Rnn) with this project I decided to make speech more normalized to be text 
and try to generalize it for arabic and english but it seems not easy , but with what I learn from my Nano Degree , I have the way to get into this project 
from my work through 4 monthes with projects from titanic to Learn Quadcopter , learning about machine learning and deeplearning which allowed me to use it easy 
to work through `speech Recognation` Project

- I am not the first one who work with `Speech Recognation` you can see some applications in this  [link](https://www.capterra.com/speech-recognition-software/)
but this applications that deployed already and has there accuracy , in my work I will take researches as my Guide, you can see [here](https://www.ijcsmc.com/docs/papers/May2015/V4I5201599a61.pdf)

## Problem Statment 
- The Goal of the project is to recognize voice into words but using deep learning like if you say Hello -> it should be recognized as Hello but it shouldn't be in only one phonems ( word ) , it will trained in many audios like in dataset [librispeech](http://www.openslr.org/12/) you have many audios you should work with to allow the recognizer to work good with you .

## Data Sets and input 
- DataSet is will be Librispeech you can find it [here](http://www.openslr.org/12/) and it will be as trained and test with it . 
I will train my model using them and try to get high accuracy but may good to make it as application for now let me try , We begin by investigating the dataset that will be used to train and evaluate My pipeline. LibriSpeech is a large corpus of English-read speech, designed for training and evaluating models for ASR. The dataset contains 1000 hours of speech derived from audiobooks. We will work with a small subset in this project, since larger-scale data would take a long while to train.

## Solution Statment 
- I will use RNN + TimeDistributed Dense Algorithmes . 
-  Fully connected layer after rnn: This model use outputs from RNN and from those we are calculating loss and probs for the spoken words. This is not good in practices as we have seen. The idea of the Model  is to add a fully connected layer between RNN part and output probs. In this way we are getting more information which we use to get better predictions. This add-on really helped in the matter of decreasing loss. As we can see on the left graph, model imediatelly started with loss of about 300. But this model didn't improve over time at both training loss and validation loss.

## Benchmark Model

## 

