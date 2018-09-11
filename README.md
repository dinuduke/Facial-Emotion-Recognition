# Emotion
This Application recognizes human faces and their corresponding emotions from a video or webcam feed. Powered by OpenCV and Deep Learning.

## Dataset
We use the FER-2013 Faces Database, a set of 28,709 pictures of people displaying 7 emotional expressions (angry, disgusted, fearful, happy, sad, surprised and neutral). The dataset quality and image diversity is not very good and you will probably get a model with bad accuracy in other applications!

You have to request for access to the dataset or you can get it on Kaggle. Download fer2013.tar.gz.

Install all the dependencies and below commands and start running with the live Demo.

```
# Dependencies
pip install keras opencv-python tensorflow numpy

# Command To Run live Demo

python emotions.py
```

## Deep Learning Model

The model used is from this [research paper](https://github.com/oarriaga/face_classification/blob/master/report.pdf) written by Octavio Arriaga, Paul G. Plöger, and Matias Valdenegro.

![Model](https://i.imgur.com/vr9yDaF.png?1)

## Credit

* Computer vision powered by OpenCV.
* Neural network scaffolding powered by Keras with Tensorflow.
* Convolutional Neural Network (CNN) deep learning architecture is from this [research paper](https://github.com/oarriaga/face_classification/blob/master/report.pdf).
* Pretrained Keras model and much of the OpenCV code provided by GitHub user [oarriaga](https://github.com/oarriaga).
* https://github.com/petercunha/Emotion