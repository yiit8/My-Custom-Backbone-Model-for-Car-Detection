# Introduction 
In this project i tried to create an object detection model to predict 8 different classes of vehicles
---------------------------------------------------------------------------------------------------------------------------------------------------
 I had two different datasets. One for object detection who had 8 classes, the other one for classification who had 2 classes
 ---------------------------------------------------------------------------------------------------------------------------------------------------
 As a starting point i thought like i would train a classification model, then use the weights of this model to fine-tune an object detection model
 ---------------------------------------------------------------------------------------------------------------------------------------------------
 But i went with difficult way, labeled 2000 classification images with labellmg and merged my datasets into one.
 ---------------------------------------------------------------------------------------------------------------------------------------------------
# Choice of Model
---------------------------------------------------------------------------------------------------------------------------------------------------
I've chosen pre-trained Faster R-CNN model for implementation. Below there is a figure showing the training stages of Faster R-CNN

![Alt text](https://production-media.paperswithcode.com/methods/Screen_Shot_2020-05-24_at_5.10.31_PM.png "Optional title")
# What next?
