# Rice_Image_Classification
It's a Deep Learning based Rice Image Classification Project using TensorFlow 2.x


Model has been trained to classify among images of 5 different categories of Rice namely Arborio,Basmati,Ipsala,Jasmine,Karacadag.

Dataset has downloaded from Kaggle.

Dataset link:https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset

Convulational Neural Network has been created using Keras Sequential API. 

The model has been trained categorical cross entropy as loss function and Adam as optimizer. Accuracy has been chosen as  metric .
Early stopping callback has been used to prevent overfitting and to retain the best weights.

Model has attained 99.11% accuarcy on test set

