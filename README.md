# Human Face Recognition

> A Human Face Recognition System to track attendance and also as a identity authentication system for course exams by authenticating the candidates and then allowing them into the exam halls

## Table of contents
* [Technologies](#technologies)
* [Running the Application](#running-the-application)
* [Snapshot](#snapshots)
* [Contact](#contact)

## Technologies
* Technologies - Python, OpenCV

## Running the Application
* Step 1: Create an Isolated Python environment and install dependencies such as numpy and OpenCV.
* Step 2: Run tester.py script on terminal to train model and to detect faces
### Training Classifier and Face Recognition
* Place Images for training the classifier in trainingImages folder.In case to train classifier to recognize multiple people then add each persons folder labeled as 0,1,2,etc and then add their names along with labels as key value pair in tester.py/videoTester.py
* To generate test images for training classifier use videoimg.py
* Place test images in TestImages folder that you want to test and add its path in tester.py and run tester.py script
* Run tester.py first since it generates training.yml file as it is used in videoTester.py
* Use "videoTester.py" script to recognize faces real-time via web cam.

## Snapshot
![Example snapshot](./snapshot/hfc1.png)

## Contact
[Hemanth Kumar Woraram](https://hemanthkumarw.com/) - feel free to contact me!
