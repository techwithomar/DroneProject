# DroneProject

Face Mask Detection


Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.

😇 Motivation
In the present scenario due to Covid-19, there is no efficient face mask detection applications which are now in high demand for transportation means, densely populated areas, residential districts, large-scale manufacturers and other enterprises to ensure safety. Also, the absence of large datasets of ‘with_mask’ images has made this task more cumbersome and challenging.

⚠️ Tech/framework used
OpenCV
Caffe-based face detector
Keras
TensorFlow
MobileNetV2
⭐ Features
Our face mask detector didn't uses any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

📁 Dataset
The dataset used can be downloaded here - Click to Download

This dataset consists of 3835 images belonging to two classes:

with_mask: 1916 images
without_mask: 1919 images
The images used were real images of faces wearing masks. The images were collected from the following sources:

Bing Search API (See Python script)
Kaggle datasets
RMFD dataset (See here)
🔑 Prerequisites
All the dependencies and required libraries are included in the file requirements.txt See here

💡 Working
Open terminal. Go into the cloned project directory folder and type the following command:
$ python3 train_mask_detector.py --dataset dataset
Now detect the face masks in images
$ python3 detect_mask_image.py --image images/pic1.jpeg
Detection in real-time video streams
$ python3 detect_mask_video.py 
🔑 Results
Our model gave 93% accuracy for Face Mask Detection after training via tensorflow-gpu==2.0.0


👏 And it's done!
Feel free to mail me for any doubts/query 📧 techwithomar1@gmail.com


❤️ Owner
Made with ❤️  by Omar Ashour

👍 Credits
https://www.pyimagesearch.com/
https://www.tensorflow.org/tutorials/images/transfer_learning
