# DIP-LAB
# Muhammad Sheraz Ajmal
# 01-134212-130

There are the Lab tasks of Digital Image Processing Lab


import cv2 
import matplotlib.pyplot as plt 
import numpy as np
#Reading the image 
image = cv2.imread("1.jpg")
print("The shape of the image is ",image.shape)
#image = image + 60
image = image * 2
plt.imshow(cv2.cvtColor(image, cv2.COLOR_BGR2RGB))
