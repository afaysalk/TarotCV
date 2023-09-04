<<<<<<< HEAD
# Playing-Cards-Computer-Vision
I trained a model using TensorFlow to detect the suit and number of playing cards given their image. I created my own dataset by taking pictures of each card, then performed pre-processing and data augmentation using rotate, zoom, brighten, and shear functions. My final dataset consisted of 39000, 180x180 grayscale images. I then trained a convolutional neural network to classify the card images.

Please check out my medium article on this project- https://medium.com/@awrd2019/image-classification-for-playing-cards-26d660f3149e.
=======
# TarotCV
Tarot Card Interpretation using Computer Vision ,ML and Chatbot
I trained a model using TensorFlow to detect the suit and number of Tarot cards given their image. I create the dataset by taking pictures of each card, then perform pre-processing and data augmentation using rotate, zoom, brighten, and shear functions. The final dataset consists of 39000, 180x180 grayscale images. I then train a convolutional neural network to classify the card images. 

## Dataset
The standard modern tarot deck consists of 78 cards divided into two groups: the major arcana, which has 22 cards, also known as trumps, and the minor arcana, which has 56 cards.To create the preliminary dataset, I simply take a single picture of each card in a 78 card deck, like so:

<img src="notebook1.png" alt="Your image title" width="250"/>


I then perform data augmentation using various transformation functions later on.

## Data augmentation functions
 I experiment with various data augmentation functions built into TensorFlow. Feel free to adjust the values and/or add additional augmentation functions. Please see the TensorFlow.Keras ImageDataGenerator api page for more details (https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator).
 
![an example of a playing card](notebook2.png)


## Training and results
During training, the training and validation accuracy both reached 99.9%. Let’s take a closer look at the loss and accuracy during the training process through the following plots.


<img src="notebook3.png" alt="Your image title" width="50%"/><img src="notebook4.png" alt="Your image title" width="50%"/>
Finally, I run the trained model on a sample of test set images. The plot below displays the sample image and the prediction of the model.

<div style="  display: block;
  width: 60%;
  margin: auto;"><img src="notebook5.png"  alt="Your image title" width="400"/> </div>
>>>>>>> 2ef93bbb8cee99dc2b8d09266c43cf262b075046
