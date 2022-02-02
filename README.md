# Caats vs Dogs Classification
## **Introduction**

Convolutional Neural Networks (CNN), a technique within the broader Deep Learning field, have been a revolutionary force in Computer Vision applications, especially in the past half-decade or so. One main use-case is that of image classification, e.g. determining whether a picture is that of a dog or cat.
<br><br><br><image src="https://media.springernature.com/lw685/springer-static/image/art%3A10.1186%2Fs40537-021-00444-8/MediaObjects/40537_2021_444_Fig7_HTML.png" style="width:100%"><br>
You don't have to limit yourself to a binary classifier of course; CNNs can easily scale to thousands of different classes, as seen in the well-known ImageNet dataset of 1000 classes, used to benchmark computer vision algorithm performance.
<br><br><br><image src="https://camo.githubusercontent.com/e70a0a0f78671c104dec3246b7faae906cec6728e4c6ed9056b8c3e0c1823467/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f612f61342f54656e736f72466c6f774c6f676f2e706e67">  <image src="https://camo.githubusercontent.com/d4542550828038568a6cb1c20934771c9c7504aaed4918685c0602ae0159bab2/68747470733a2f2f75706c6f61642e77696b696d656469612e6f72672f77696b6970656469612f636f6d6d6f6e732f632f63392f4b657261735f4c6f676f2e6a7067"><br>
In the past couple of years, these cutting edge techniques have started to become available to the broader software development community. Industrial strength packages such as [Tensorflow](https://www.tensorflow.org/) have given us the same building blocks that Google uses to write deep learning applications for embedded/mobile devices to scalable clusters in the cloud -- *Without having to handcode the GPU matrix operations, partial derivative gradients, and stochastic optimizers that make efficient applications possible.*

On top of all of this, are user-friendly APIs such as [Keras](https://keras.io/) that abstract away some of the lower level details and allow us to focus on rapidly prototyping a deep learning computation graph.

### **Project Description**

As an introductory project for myself, I have tried Binary-Image-Classification of Cats vs Dogs dataset.<br>
  The total images are as follows :<br>
  Total training cat images : 8750<br>
  Total training dog images : 8750<br>
  Total validation cat images : 3750<br>
  Total validation dog images : 3750<br>
**The dataset is from kaggle**

### Objective

The main objective of this project is to get hands-on with TensorFlow and get used to the syntax.

### **Approach**
  
  -CNN model using 'relu' and 'sigmoid'.
  -Classification and loss as 'binary-crossentropy'
  
### **Run The Model**
  
  To run the model on your device , open the code in python compiler (Jupeter noteook/colab).
  Now run the Predict section of the code and upload the image from your device or from URL.
  
### **Results**

After tuning a hard-coded model the accuracy of the model in test reached till 85%

  The Model and Project both are not yet fully optimised and the work is in Progress. Surely open to help & Ideas !
