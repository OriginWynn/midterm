# midterm
使用Google Colab

#用到的模型:
from tensorflow.keras.applications.vgg16 import VGG16
from tensorflow.keras.preprocessing import image
from tensorflow.keras.applications.vgg16 import preprocess_input
from tensorflow.keras import layers
from tensorflow.keras.models import Model
from tensorflow.keras.utils import to_categorical
import numpy as np
import os
import cv2
from google.colab.patches import cv2_imshow
from IPython.display import Image
import matplotlib.pyplot as plt
from tensorflow.keras.optimizers import Adam
import keras
import tensorflow_addons as tfa
import tensorflow as tf

.zip檔裡是訓練資料集全部都需要才能解壓縮

test是訓練完後拿來測試的照片
