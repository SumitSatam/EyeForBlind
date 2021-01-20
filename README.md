# EyeForBlind

## Idea of the project : 
Caption generation through a CNN-RNN model further to be converted to speech using a text to speech library for a visually challenged person for understanding the content of an image in the form of speech.

## Problem statement: 

To create a deep learning model which can explain the content of an image in the form of speech through Caption generation with attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. 
This problem statement is an application of both Deep Learning and Natural Language processing. The features of an image will be extracted by CNN based encoder and this will be decoded by an RNN model

The project is an extended application of [Show, Attend and Tell: Neural Image Caption Generation with Visual Attention - paper.](https://arxiv.org/abs/1502.03044)

The dataset used is Flickr8K dataset which consists of sentence-based image description having a list of 8,000 images that are each paired with five different captions which provide clear descriptions of the salient entities and events of the image.

## Project Pipeline

The project pipeline can be briefly summarized in the following four steps:

* Data Understanding: Here, you need to load the data and understand the representation 
* Data preprocessing: In this step, you will process both images & captions to the desired format.
* Train/Test Split: Combine both images & captions to create the train & test dataset.
* Model-Building: This is the stage where you will create your image captioning model by building Encoder , Attention & Decoder model
* Model Evaluation: Evaluate the models using greedy search & BLEU score
