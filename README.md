![face1](https://user-images.githubusercontent.com/8762634/129442046-7cfab7c7-db3a-45b1-8d00-12733c6cbd10.PNG)
![face3](https://user-images.githubusercontent.com/8762634/129442065-6c1ae539-59c8-45fc-8708-9ff2b518e9dd.PNG)
# FaceMaskDetection-with-opencv
FaceMask Detction with opencv python, keras and tensorflowFace Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.


😇 Motivation
In the present scenario due to Covid-19, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Also, the absence of large datasets of ‘with_mask’ images has made this task more cumbersome and challenging.

📁 Dataset
The dataset used can be downloaded here - Click to Download

This dataset consists of 4095 images belonging to two classes:

with_mask: 2165 images
without_mask: 1930 imagesAll the dependencies and required libraries are included in the file requirements.txt See here

🚀  Installation
Clone the repo
$ git clone https://github.com/musasizifrancis/FaceMaskDetection-with-opencv.git
Change your directory to the cloned repo
$ cd Face-Mask-Detection
Create a Python virtual environment named 'test' and activate it
$ virtualenv test
$ source test/bin/activate
Now, run the following command in your Terminal/Command Prompt to install the libraries required
$ pip3 install -r requirements.txt
💡 Working
Open terminal. Go into the cloned project directory and type the following command:
$ python3 train_mask_detector.py --dataset dataset
To detect face masks in an image type the following command:
$ python3 detect_mask_image.py --image images/pic1.jpeg
To detect face masks in real-time video streams type the following command:
$ python3 detect_mask_video.py 

