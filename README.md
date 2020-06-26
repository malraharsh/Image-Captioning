# Image Captioning using LSTM with Flickr data

### Making images speak

This repo contains my work regarding the project image captioning. 

# Project Motivation

The aim of my project is to take any image provided by the user, and then use my trained model to describe the current event of the image. This is the implementation of model using LSTM and Dense layers to process then input and then combine them to predict the next work for our caption use Deep learning methods.

# Files Description

The image captioning notebook contains all the necessary codes. These includes -

1. Prerequisites
2. Collecting the data
3. Analysis of data
4. Cleaning of data
5. Preprocessing Images
6. Preprocessing Captions
7. Using Generator Function
8. Word Embeddings
9. Model Architecture
10. Evaluating the Model

## Getting Started

### Prerequisites
1. **Python 3** 
2. **Python libraries**: numpy, pandas, scipy, matplotlib, keras, tensorflow 


### Download the dataset

You have two possibilities:

1. The flickr8k dataset used in this project has been downloaded from: [Flickr8k_Dataset.zip]
(https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip)

2. Download the caption from [here](https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip
).


### Launch Jupyter Notebook

The jupyter notebook can be opened [here] (in Colab). To avoid dealing with libraries. As all the necessary libraries are present here.

## References 

1. Understanding embeddings [here](https://www.analyticsvidhya.com/blog/2017/06/word-embeddings-count-word2veec/)
2. Medium Blogpost [here](https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8)
3. The notebook [here](https://github.com/hlamba28/Automatic-Image-Captioning/blob/master/Automatic%20Image%20Captioning.ipynb)


## Built With

* [Python](https://www.python.org/) - Python programming language
* [Colab](https://colab.research.google.com/drive/1474TYkl-WsrmLfbj-_vqWge9YU5NS17R#scrollTo=YsJD2Ic4DmxR) - Google Colab

## Acknowledgments

* Acknowledgement is given to jBrownlee blogs providing both the image dataset and caption. And to Google Colab for their free Servies.
