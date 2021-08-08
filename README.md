# Face-Detection-of-Actors-in-Movie-Scene

DOMAIN: Entertainment

CONTEXT: Company X owns a movie application and repository which caters movie streaming to millions of users who on subscription basis.
Company wants to automate the process of cast and crew information in each scene from a movie such that when a user pauses on the
movie and clicks on cast information button, the app will show details of the actor in the scene. Company has an in-house computer vision
and multimedia experts who need to detect faces from screen shots from the movie scene.

DATA DESCRIPTION:  WIDER FACE dataset is a face detection benchmark dataset which has 32,203 images and label 393,703 faces with a high degree of variability in scale, pose
and occlusion.The dataset comprises of images and its mask where there is a human face. http://mmlab.ie.cuhk.edu.hk/projects/WIDERFace/

PROJECT OBJECTIVE: I have built a Face detection model from training images.First I have imported the dataset and created features (images) and labels (mask)
using that data.Then I have designed a face mask detection model using U-Net along with MobileNet as pre-trained transfer learning model. I have designed my own
Dice Coefficient and Loss function. 
 
