# Fruit Classifier Model

This repository contains code and a trained Keras model for classifying fruits using image recognition and machine learning. The model was trained on a dataset of fruit images from the Fruits &amp; Vegetables by Jorge B's dataset.

The model was trained using a transfer learning approach, where a pre-trained convolutional neural network (CNN) model was fine-tuned on the fruit image dataset. The pre-trained CNN model was the ResNet50 architecture with weights trained on the ImageNet dataset.

To use the model, simply load it into a TensorFlow or Keras session and pass it a fruit image. The model will output a probability distribution over the 5 fruit categories. The category with the highest probability is the predicted fruit type.


## Acknowledgements

This model was trained using Google's Teachable Machine platform. The code for training the model was generated by Teachable Machine and modified to work with TensorFlow 2.0. The code for loading the model and making predictions was also generated by Teachable Machine and modified to work with TensorFlow 2.0.

## Dataset Resources

No description

This dataset is from Kaggle and can be found [here](https://www.kaggle.com/datasets/jorgebailon/fruits-vegetables).

## Disclaimer

This model is for research purposes only and should not be used to identify or classify fruits in a real-world setting.
