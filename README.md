# Logo-segmentation
[TensorFlow](https://www.tensorflow.org/) | [Keras](https://keras.io/)


This tutorial focuses on the task of image segmentation, using a modified U-Net.

What is image segmentation?
So far you have seen image classification, where the task of the network is to assign a label or class to an input image. However, suppose you want to know where an object is located in the image, the shape of that object, which pixel belongs to which object, etc. In this case you will want to segment the image, i.e., each pixel of the image is given a label. Thus, the task of image segmentation is to train a neural network to output a pixel-wise mask of the image. This helps in understanding the image at a much lower level, i.e., the pixel level. Image segmentation has many applications in medical imaging, self-driving cars and satellite imaging to name a few.

The dataset that will be used for this tutorial is the logo detection dataset. The dataset consists of images, their corresponding labels, and pixel-wise masks. The masks are basically labels for each pixel. Each pixel is given one of two categories :

Class 1 : Pixel belonging to the logo.
Class 2 : Pixel surrounding the logo.

<img src=logo.png alt="Segmented logo" width="800">
