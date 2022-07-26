# Detection-of-Animals-Using-Machine-Learning-To-Prevent-Intrusion-At-Any-Specified-Place
Detection of animals and people using Single-Shot Multi-Box Detector Machine Learning model with Google's TensorFlow Lite where data is used from camera live feed.

## Abstract
Animal intrusion is a serious issue in many places like agricultural fields, highways, remote villages, and base stations of various camps. This affects food security as the intrusion of animals will damage yield in agricultural lands, thus reducing farmers' profit. Also, intrusion on highways where vehicles move at a faster pace might come into collision with them, leading to disastrous accidents, and people in remote villages and camps are prone to wild animals invading unknowingly. There must be some way to detect the animals before they come to areas where they shouldn’t be and take necessary precautions to prevent their intrusion and its consequences. In this work, a solution using the advancements in Machine Learning algorithm techniques, to detect animals is proposed. Machine Learning algorithms like Single Shot Detection are used to detect the animals and classify them based on their category to know whether it’s a threat or not to take necessary precautions in advance. Also, integrating the already made open-source APIs into this project improves further in-depth analysis of the situations. This Machine Learning solution can be used to detect animals in advance and take necessary precautions such that animal intrusion damage consequences will be avoided.

#### KEYWORDS
Single Shot Detector (SSD), Convolutional Neural Network (CNN), TensorFlow, Machine Learning, Application Programming Interface (API), Image Processing, Animal Intrusion, Computational

## Requirements
1. OpenCV
2. TensorFlow
3. TensorFlow Lite Runtime
4. Python [and other python libraries as needed]

## Programs Information
#### TFLite_Camera.py
Runs the machine learning object detection model using any connected usb camera or webcam [default video capture device].
#### TFLite_Video.py
Runs the machine learning object detection model in a specified video.
#### TFLite_Image.py
Runs the machine learning object detection model in a directory of images or in an image.

#### Arguments To Run The Programs
1. **--modeldir=** Provide the folder directory where .tflite and label map files are available. 
2. **--video=** Provide the video file directory to detect objects. 
3. **--image=** Provide a folder directory where all images are present. 
4. **--imagedir=** Provide an image directory to detect objects. 
5. **--edgetpu=** Provide Edge TPU directory if available.

## Conclusion
Agricultural yield protection, avoiding accidents on national highways, and injuries in remote areas like villages & base stations because of animal intrusion will be detected beforehand with the use of the Single-Shot Multi-Box Detector machine learning model with the use of Google’s TensorFlow APIs. SSD algorithm performance is good to detect animals and persons quickly in real-time using the camera’s live feed but the accuracy of the detected object will not be near 100%. Compared to other types of a convolutional neural network like R-CNN which mainly focuses on accuracy rather than speed of detection, it will not be so useful for IoT or other mobile ARM-based devices for this application as processor power in these small devices will be low. SSD has the perfect qualities to work with these types of devices for faster detection and identifying objects without any miss in any frame. Hence, the animal intrusion is prevented with the proposed work in this paper.

#### FUTURE WORKS
An app-based prototype can be developed such that it will be user-friendly and can be more mobile 
so that it can be taken anywhere for the detection of animal intrusion. 

## Guide
#### Please refer the report [Final Report.pdf] to get the better understanding of this project.

#### SPECIAL THANKS TO "SASTRA DEEMED TO BE UNIVERSITY" [Official Webpage](https://www.sastra.edu/)
##### Thanks to EdjeElectronics - TensorFlow Lite Object Detection on Android and Raspberry Pi [Repository Link](https://github.com/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi)
