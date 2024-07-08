# Image-Caption-Generator
# What is Image Caption Generator?
Image caption generator is a task that involves computer vision and natural language processing concepts to recognize the context of an image and describe them in a natural language like English.

The objective of our project is to build a working model of Image caption generator by implementing CNN with LSTM.

In this Python project, we will be implementing the caption generator using CNN (Convolutional Neural Networks) and LSTM (Long short term memory). The image features will be extracted from VGG16 which is a CNN model trained on the imagenet dataset and then we feed the features into the LSTM model which will be responsible for generating the image captions.

# The Dataset

Thanks to Jason Brownlee for providing a direct link to download the dataset (Size: 1GB).

- Flicker8k_Dataset https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_Dataset.zip
- Flickr_8k_text https://github.com/jbrownlee/Datasets/releases/download/Flickr8k/Flickr8k_text.zip

The Flickr_8k_text folder contains file Flickr8k.token which is the main file of our dataset that contains image name and their respective captions separated by newline(“\n”).

**Downloaded from dataset:**

- Flicker8k_Dataset – Dataset folder which contains 8091 images.
- Flickr_8k_text – Dataset folder which contains text files and captions of images.
