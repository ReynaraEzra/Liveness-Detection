# Liveness-Detection
An overview of face liveness detection

<hr>

## Background
![dataset.png](https://d1tzzns6d79su2.cloudfront.net/uploads/embedded_image/c71c2d888583b39413a3626722d03eda2ba6ea938672f974efaf9a86b98b4bdc/87d93aad-d1c9-4c74-8121-1878983c2a81.webp)

Liveness detection is the application of the field of computer vision in biometrics which gives the system the ability to be able to recognize several biometric objects such as fingerprints, faces and so on so as to be able to distinguish between pseudo/fake biometric objects and real biometric objects. Create image-based anti-spoofing model by classifying whether its considered as live or fake

## Audience
The application of algorithms to detect faces has been used in several companies. But face detection like this can be spoofed by using a print of someone's face or wearing a mask. By building face liveness detection, we will see if the detected image is a human or a human image.

## Dataset
In this problem, we will use two datasets, namely MSU-MFSD and CelebA-Spoof. MSU-MFSD dataset contains as many as 280 video recordings, both genuine and fake. Made from 35 participants. The original dataset was made with 2 different devices, namely a laptop camera and an android. Meanwhile, the fake dataset was made with 2 different devices, namely iPhone and Canon camera. The dataset structure consists of training and testing. Training is made of 15 subjects and 120 videos, while testing is made of 40 subjects and 160 videos. CelebA-Spoof dataset contains 625,537 images from 10,177 subjects covering 43 attributes such as the face, illumination, environment, and spoof. But in this repository, we will only use the second one. You can access the dataset via https://github.com/Davidzhangyuanhan/CelebA-Spoof (github) or https://www.kaggle.com/attentionlayer241/celeba-spoof-for-face-antispoofing (kaggle)

## Plan
The problem to be solved is to create a model to perform face liveness detection. The information to be obtained is to find out whether the detected face is genuine or not. The model creation process starts with preprocessing image data, building deep learning models using the Convolutional Neural Network architecture, improving model performance with tuning parameters to select the best model, and making predictions.

## Note
Description of the file in the repository.

Dataset Folder :
- `Live Folder` : List of Real Images
- `Spoof Folder` : List of Spoof Images
- `Dataset 59 Images.zip` : 59 images (29 Live Images & 30 Spoof Images)
- `Dataset 400 Images.zip` : 400 images (200 Live Images & 200 Spoof Images)
- `Dataset 600 Images.zip` : 600 images (300 Live Images & 300 Spoof Images)

Model Folder :
- `Jupyter Notebook File`: .ipynb file 
- `model.h5` : Model 
- `model_1.h5` : Model From LivenessNet 

## Reference 
Dataset :
- https://www.kaggle.com/attentionlayer241/celeba-spoof-for-face-antispoofing
- https://github.com/Davidzhangyuanhan/CelebA-Spoof

Github :
- https://github.com/anand498/Face-Liveness-Detection/tree/master/livenessdetect
- https://github.com/dwang0721/Facial-Recognition-using-Fourier-Transform
- https://github.com/Prem95/face-liveness-detector
- https://github.com/sakethbachu/Face-Liveness-Detection

Journal/Article :
- https://www.thalesgroup.com/en/markets/digital-identity-and-security/government/inspired/liveness-detection
- https://www.pyimagesearch.com/2019/03/11/liveness-detection-with-opencv/
- https://www.researchgate.net/publication/334507381_Insight_on_Face_Liveness_Detection_A_Systematic_Literature_Review
- https://arxiv.org/ftp/arxiv/papers/1903/1903.05369.pdf
- https://arxiv.org/ftp/arxiv/papers/1405/1405.2227.pdf
- https://towardsdatascience.com/a-friendly-introduction-to-siamese-networks-85ab17522942
- https://paperswithcode.com/task/face-anti-spoofing
