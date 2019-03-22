
# Biostat M280 Homework 4


## Question 1

For question 1, we reproduce the result in [Neural style transfer with eager execution and Keras](https://blogs.rstudio.com/tensorflow/posts/2018-09-10-eager-style-transfer/). The code uses neural style transfer techniques to transmute an original picture into the 'style' of a second picture.

We tuned the image_shape parameter by changing it from c(128,128,3) to c(256,256,3) and c(512,512,3). This means we broke the pictures in to more pixels which can make a higher resolution of the output picture. 


![image](https://github.com/dw6ja/biostatm280-winter2019-hw4/blob/develop/Q1/q1.png)


Please see the Rmd file for the whole report. 


## Question 2

For question 2, we develop an app "Foodie" such that a user takes a photo of a meal and the app will recognize and record the type of food. 

**Here is our prototype app demo**


![Output sample](https://github.com/dw6ja/biostatm280-winter2019-hw4/blob/develop/Foodie/Foodie%20Demo.gif)


## Tech stack:

* TensorFlow v1.10
* Xcode 10.1
* Food101 Core ML model
* Inception v3 Core ML model


## Author

Xinrui Zhang, Yun Han, Juehao Hu, Diyang Wu, Edward Yu
