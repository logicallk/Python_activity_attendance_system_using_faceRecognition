
# Face based attendance system using python and openCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)                 
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/) 

### What steps you have to follow??
- Download or clone my Repository to your device
- Install all requirement below mention(this will install required package for project)
- Create a `TrainingImage` folder in a project folder.
- open `attendance.py` and `automaticAttendance.py`, change all the path accoriding to your system
- Run `attandance.py` file

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.

### Project Requirement
---Code Requirements---
Python 3.6+
Opencv(pip install opencv-python)
Tkinter(Available in python)
PIL (pip install Pillow)
Pandas(pip install pandas)
Numpy(pip install numpy)
Pillow (pip install Pillow)
****************************************************************************
haarcascade_frontalface_default.xml  ->>>> 
haarcascades - the folder contains trained classifiers for detecting objects
               of a particular type, e.g. faces (frontal, profile), pedestrians etc.
               Some of the classifiers have a special license - please,
               look into the files for details.
https://github.com/opencv/opencv/tree/master/data/haarcascades
*********************************************************************
Editor - Visual studio code

--Notes--
It will require high processing power(I have 8 GB RAM & 1 GB Nvidia GT740M Graphic Card)
Noisy image can reduce your accuracy so quality of images matter.

### Requirement
numpy==1.16.1
opencv-contrib-python==4.2.0.34
opencv-python==4.2.0.34
openpyxl==3.0.3
pandas==1.0.3
Pillow==7.1.1
pyttsx3==2.71





