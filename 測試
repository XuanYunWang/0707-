import numpy as np
import pandas as pd
from keras.utils import np_utils
from keras.datasets import mnist
import matplotlib.pyplot as plt
(x_train_img,y_train_lab),(x_test_img,y_test_lab) = mnist.load_data()
print('train data = ', len(x_test_img), len(y_test_lab))
print(x_train_img.shape,x_test_img.shape)
print(y_train_lab.shape,y_test_lab.shape)
print('train data=',len(x_train_img))
def plot_image(image):
    fig=plt.gcf()
    fig.set_size_inches(2,2)
    plt.imshow(image,cmap='binary')
    plt.show()
for i in range(10):
    plot_image(x_train_img[i])
    print("ans:"+str(y_train_lab[i]))


