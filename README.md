# MR_Object-detection-image_Ver1
Object detection Image

## Building an Object Detection Model from Scratch in Python

When we’re shown an image, our brain instantly recognizes the objects contained in it. On the other hand, it
takes a lot of time and training data for a machine to identify these objects. But with the recent advances in
hardware and deep learning, this computer vision field has become a whole lot easier and more intuitive.

https://www.analyticsvidhya.com/blog/2018/06/understanding-building-object-detection-model-python/ https://www.analyticsvidhya.com/blog/2018/07/top-10-pretrained-models-get-started-deep-learning-part-1-computer-vision/


### Step 1: Create an Anaconda environment with python version 3.6.
<br/>conda create -n retinanet python=3.6 anaconda

### Step 2: Activate the environment and install the necessary packages.
<br/>activate retinanet conda install tensorflow numpy scipy opencv pillow matplotlib h5py keras

### Step 3: Then install the ImageAI library.
<br/>pip install https://github.com/OlafenwaMoses/ImageAI/releases/download/2.0.1/imageai-2.0.1-py3-none-any.whl

### Step 4: Now download the pretrained model required to generate predictions.
<br/>This model is based on RetinaNet (a subject of a future article). Click on the link to download – RetinaNet Pretrained model <br/>https://github.com/fizyr/keras-retinanet/releases
<br/>>Step 5: Copy the downloaded file to your current working folder
<br/>>Step 6: Download the image from this link. Name the image as image.png
<br/>>Step 7: Open jupyter notebook (type jupyter notebook in your terminal) and run

## Image to Predict:

![](Images/car.jpg?raw=true)

<br/>Prediction:
<br/>car : 76.26890540122986
<br/>--------------------------------
<br/>car : 94.30564641952515
<br/>--------------------------------
<br/>car : 70.49705386161804
--------------------------------
