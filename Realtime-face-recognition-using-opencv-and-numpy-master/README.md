# Real-time Face Recognition 

Face Recognition using OpenCV in Python

# Prerequisites
•	Numpy (Install Numpy via anaconda: conda install numpy)

•	OpenCV (Install OpenCV via anaconda: conda install -c menpo opencv)

# Running the tests

Run Tester.py script on commandline to train recognizer on training images and also predict test_img: “python tester.py”

1.Place some test images in TestImages folder that you want to predict in tester.py file

2.Place Images for training the classifier in trainingImages folder.If you want to train clasifier to recognize multiple people then add each persons folder in separate label mares as 0,1,2,etc and then add their names along with labels in tester.py/videoTester.py file in 'name' variable.

3.To generate test images for training classifier use videotoimg.py file.

4.To do test run via tester.py give the path of image in test_img variable

5.Use "videoTester.py" script for predicting faces realtime via your webcam.(But ensure that you run tester.py first since it generates training.yml file that is being used in "videoTester.py" script.

# References
1.https://towardsdatascience.com/face-recognition-how-lbph-works-90ec258c3d6b

2.https://pythonprogramming.net/haar-cascade-face-eye-detection-python-opencv-tutorial/

3.https://www.geeksforgeeks.org/face-detection-using-python-and-opencv-with-webcam/?fbclid=IwAR3MH4ftHgyYimYZziWSjwHMk8yD2rpTiSIfS_FXIEUKGKkcFz0PGWaZuGQ

4.https://github.com/neha01/FaceRecognition
