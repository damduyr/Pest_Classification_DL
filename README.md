# Pest_Classification_DL

Pest Classification Using Deep Learning tackles a crucial agricultural challenge by harnessing Deep 
Learning, Convolutional Neural Networks (CNNs), Digital Image Processing, and Computer Vision to 
create an efficient pest classification system. The primary goal is accurate pest species identification in 
agricultural settings, achieved through diverse dataset collection, specialized CNN design, and real-time 
classification. This project aspires to enhance crop protection and agricultural productivity. Challenges 
include sensitivity to occlusion, class imbalance, dataset quality, and appearance variability in pest 
images. To overcome these, the project adopts CNNs, periodic model retraining, specialized CNN 
architecture, diversified training datasets (especially Indian pests), and advanced deep learning models 
to revolutionize pest management and promote sustainable agriculture.

### *Requirements*

Download Pest Dataset from the link: https://drive.google.com/drive/folders/1qZAu-Mt7-X5I7Oqv5dJpHQk-NP5L80co?usp=drive_link

### *Libraries used*:- 

import tensorflow as tf

from tensorflow.keras import models, layers

import matplotlib.pyplot as plt

from tensorflow.keras.layers import Dense, Flatten, GlobalAveragePooling2D, Dense, Dropout,Conv2D,MaxPooling2D

from tensorflow.keras import optimizers

from tensorflow.keras.datasets import mnist

from tensorflow.keras.models import Sequential

from tensorflow.keras.layers import Flatten, Dense, Conv2D, MaxPooling2D

from tensorflow.keras.layers import Dropout, BatchNormalization, LeakyReLU, Activation

from tensorflow.keras.callbacks import Callback, EarlyStopping, ReduceLROnPlateau

from tensorflow.keras.preprocessing.image import ImageDataGenerator

### *Flow Chart* 

![image](https://github.com/damduyr/Pest_Classification_DL/assets/114305300/a5d8fc96-ad79-48a6-aaf5-48839b6b4d42)


