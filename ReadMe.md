#  Face Recognition

Facial recognition is a biometric software application capable of uniquely identifying or verifying a person by comparing and analyzing patterns based on the person's facial contours. Facial recognition is mostly used for security purposes, though there is increasing interest in other areas of use. In fact, facial recognition technology has received significant attention as it has potential for a wide range of application related to law enforcement as well as other enterprises.


# Files Provided

I have provided code for Face Detection, Age & Gender Detection and Emotion Recognition.

## Create files and folders

 - Emotion Recognition
 - Face Detection
 - Age & Gender Detection

# Features


#### Find faces in pictures

Find all the faces that appear in a picture:

[![](https://cloud.githubusercontent.com/assets/896692/23625227/42c65360-025d-11e7-94ea-b12f28cb34b4.png)](https://cloud.githubusercontent.com/assets/896692/23625227/42c65360-025d-11e7-94ea-b12f28cb34b4.png)

#### [](https://github.com/ageitgey/face_recognition#find-and-manipulate-facial-features-in-pictures)Find and manipulate facial features in pictures

Get the locations and outlines of each person's eyes, nose, mouth and chin.

[![](https://cloud.githubusercontent.com/assets/896692/23625282/7f2d79dc-025d-11e7-8728-d8924596f8fa.png)](https://cloud.githubusercontent.com/assets/896692/23625282/7f2d79dc-025d-11e7-8728-d8924596f8fa.png)

Finding facial features is super useful for lots of important stuff. But you can also use it for really stupid stuff like applying  [digital make-up](https://github.com/ageitgey/face_recognition/blob/master/examples/digital_makeup.py)  (think 'Meitu'):

[![](https://cloud.githubusercontent.com/assets/896692/23625283/80638760-025d-11e7-80a2-1d2779f7ccab.png)](https://cloud.githubusercontent.com/assets/896692/23625283/80638760-025d-11e7-80a2-1d2779f7ccab.png)

#### [](https://github.com/ageitgey/face_recognition#identify-faces-in-pictures)Identify faces in pictures

Recognize who appears in each photo.

[![](https://cloud.githubusercontent.com/assets/896692/23625229/45e049b6-025d-11e7-89cc-8a71cf89e713.png)](https://cloud.githubusercontent.com/assets/896692/23625229/45e049b6-025d-11e7-89cc-8a71cf89e713.png)

You can even use this library with other Python libraries to do real-time face recognition:

[![](https://cloud.githubusercontent.com/assets/896692/24430398/36f0e3f0-13cb-11e7-8258-4d0c9ce1e419.gif)](https://cloud.githubusercontent.com/assets/896692/24430398/36f0e3f0-13cb-11e7-8258-4d0c9ce1e419.gif)

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Requirements

 - Python 3
 - OpenCV
 - TensorFlow
 - Keras
 - pandas
 - NumPy

# To Run The Code

  To run the face detection, open face detection floader and run
 - Image.py to give image as input
 - Video.py to give video as input
 - Live.py to get input from your webcam
 
 To run age & gender code , open Age & gender floater and run the Age&Gender.py

To run Emotion Recognition code , open Emotion Recognition and 

 - First train the dataset(the dataset should be in .csv), and it can be trained from Training.py code.
 - After training run Emotion Recognition.py

## Python Code Examples


#### Face Detection

-   [Find faces in a photograph](https://github.com/ageitgey/face_recognition/blob/master/examples/find_faces_in_picture.py)
-   [Find faces in a photograph (using deep learning)](https://github.com/ageitgey/face_recognition/blob/master/examples/find_faces_in_picture_cnn.py)
-   [Find faces in batches of images w/ GPU (using deep learning)](https://github.com/ageitgey/face_recognition/blob/master/examples/find_faces_in_batches.py)
-   [Blur all the faces in a live video using your webcam (Requires OpenCV to be installed)](https://github.com/ageitgey/face_recognition/blob/master/examples/blur_faces_on_webcam.py)

#### [](https://github.com/ageitgey/face_recognition#facial-features)Facial Features

-   [Identify specific facial features in a photograph](https://github.com/ageitgey/face_recognition/blob/master/examples/find_facial_features_in_picture.py)
-   [Apply (horribly ugly) digital make-up](https://github.com/ageitgey/face_recognition/blob/master/examples/digital_makeup.py)

#### [](https://github.com/ageitgey/face_recognition#facial-recognition)Facial Recognition

-   [Find and recognize unknown faces in a photograph based on photographs of known people](https://github.com/ageitgey/face_recognition/blob/master/examples/recognize_faces_in_pictures.py)
-   [Identify and draw boxes around each person in a photo](https://github.com/ageitgey/face_recognition/blob/master/examples/identify_and_draw_boxes_on_faces.py)
-   [Compare faces by numeric face distance instead of only True/False matches](https://github.com/ageitgey/face_recognition/blob/master/examples/face_distance.py)
-   [Recognize faces in live video using your webcam - Simple / Slower Version (Requires OpenCV to be installed)](https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_webcam.py)
-   [Recognize faces in live video using your webcam - Faster Version (Requires OpenCV to be installed)](https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_webcam_faster.py)
-   [Recognize faces in a video file and write out new video file (Requires OpenCV to be installed)](https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_from_video_file.py)
-   [Recognize faces on a Raspberry Pi w/ camera](https://github.com/ageitgey/face_recognition/blob/master/examples/facerec_on_raspberry_pi.py)
-   [Run a web service to recognize faces via HTTP (Requires Flask to be installed)](https://github.com/ageitgey/face_recognition/blob/master/examples/web_service_example.py)
-   [Recognize faces with a K-nearest neighbors classifier](https://github.com/ageitgey/face_recognition/blob/master/examples/face_recognition_knn.py)
-   [Train multiple images per person then recognize faces using a SVM](https://github.com/ageitgey/face_recognition/blob/master/examples/face_recognition_svm.py)

## Thanks

Thanks to everyone who works on all the awesome Python data science libraries like numpy, scipy, scikit-image, pillow, etc, etc that makes this kind of stuff so easy and fun in Python.

