# Ship_Detection_CNN
This notebook contains a process of creating an end to end CNN model using tensorflow

The goal of this project is to learn and try out different techniques used in computer vision, specifically building, and deploying a CNN model. This will be a beginner friendly project that will focus on EDA, preprocessing techniques, and the evaluation of models. 

The plan is to create an image classification model using Convolutions for feature extraction. Then to pass through a Region Proposal Network(RPN) to create a faster R-CNN model for object detection using TensorFlow as a framework. 

**A Convolutional Neural Network**, also known as CNN, is a class of neural networks that specializes in processing data that has a grid-like topology, such as an image. A digital image is a binary representation of visual data. CNN can recognize patterns and features in images by performing convolution and pooling operations on the input images to extract relevant information. 
**Region-based CNNs** or regions with CNN features (R-CNNs) are also among many pioneering approaches of applying deep learning to object detection.To reduce region proposals without loss of accuracy, the faster R-CNN proposes to replace selective search with a region proposal network

![image.png](attachment:5b3ada7a-fc63-4713-9dc5-c5d4841390f7.png) ![download.png](attachment:c03784f0-2c36-4143-96d8-0d53370356cf.png)

**Summery of data set**

[The Dataset](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery)

The dataset consists of images extracted from Planet satellite imagery collected over the San Francisco Bay and San Pedro Bay areas of California. The aim of this dataset is to help address the difficult task of detecting the location of large ships in satellite images. Automating this process can be applied to many issues including monitoring port activity levels and supply chain analysis.

The dataset consists of 4000 80x80 RGB images labeled with either a "ship" or "no-ship" The pixel value data for each 80x80 RGB image is stored as a list of 19200 integers within the data list. The first 6400 entries contain the red channel values, the next 6400 the green, and the final 6400 the blue. The image is stored in row-major order so that the first 80 entries of the array are the red channel values of the first row of the image.
