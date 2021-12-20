# Facial-Expression-Recognizer-using-Deep-Learning
This project classifies different types of facial expressions and implements in real time data. It means we can classify facial expressions 
from real time images and videos.The dataset is available on kaggle. The dataset contains grayscale images which are 48x48 in dimension.The
task is to categorize each face based on emotions shown in image into one of the seven categories: 0=Angry,1=Disgust,2=Fear,
3=Happy,4=Sad,5=Surprise,6=Neutral.
Data is divided into two folders train and test which are further divided into 7 subfolders. These subfolders contain images for
7 facial expressions.
EfficientNetB2 is used as a backbone model.
Tensorflow , cv2 and dlib libraries are used for real time predictions.

