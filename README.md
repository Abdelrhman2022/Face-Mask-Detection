  
<h1 align="center">Face Mask Detection</h1>



<div align= "center">
  
  ![Demo Face Mask Detection](https://github.com/Abdelrhman2022/Face-Mask-Detection/blob/main/Demo%20video%20of%20the%20(Face-Mask-Detection)%20Real-Time.gif)
  
  <h4>Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams, The CNN manages to get an accuracy of 99.38% on the training set and 99.44% on the test set. Then the stored weights of this CNN are used to classify as mask or no mask, in real time, using OpenCV. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.</h4>
  

</div>




## :file_folder: Dataset
The dataset used can be downloaded here - [Click to Download](https://github.com/chandrikadeb7/Face-Mask-Detection/tree/master/dataset)

This dataset consists of __4095 images__ belonging to two classes:
*	__with_mask: 2165 images__
*	__without_mask: 1930 images__

The images used were real images of faces wearing masks. The images were collected from the following sources:

* __Kaggle datasets__ ([See here](https://www.kaggle.com/datasets/vijaykumar1799/face-mask-detection)) 
* __RMFD dataset__ ([See here](https://github.com/X-zhangyang/Real-World-Masked-Face-Dataset))


## :star: Features
Our face mask detector doesn't use any morphed masked images dataset and the model is accurate. Owing to the use of MobileNetV2 architecture, it is computationally efficient, thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

## :key: Results

#### Our model achive above 99% accuracy for Face Mask Detection after training via MobileNetV2 architecture


####          
<p align="center">
  <img src="https://github.com/Abdelrhman2022/Face-Mask-Detection/blob/main/summary.PNG" alt="summary" />
</p>


#### We got the following accuracy/loss training curve plot
<p align="center">
  <img src="https://github.com/Abdelrhman2022/Face-Mask-Detection/blob/main/plot.png" alt="summary" />
</p>
