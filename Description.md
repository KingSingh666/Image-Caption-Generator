**What is a CNN?**

A Convolutional Neural Network (CNN) is a specialized type of deep neural network designed to process data with an input shape resembling a 2D matrix, making it particularly effective for handling images. 

CNNs are widely used for image classification tasks, such as determining whether an image depicts a bird, a plane, or even Superman.

**What is an LSTM?**

LSTM, or Long Short-Term Memory, is a type of Recurrent Neural Network (RNN) that excels in sequence prediction problems. It can predict the next word in a sequence based on the previous text. LSTMs have proven more effective than traditional RNNs by overcoming their limitations related to short-term memory. LSTMs can retain relevant information throughout the processing of inputs and use a forget gate to discard non-relevant information.

This is what an LSTM cell looks like:

**Image Caption Generator Model**

So, to make our image caption generator model, we will be merging these architectures. It is also called a CNN-RNN model.

CNN is used for extracting features from the image. We will use the pre-trained model Xception.
LSTM will use the information from CNN to help generate a description of the image
