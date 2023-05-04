# Object and People Recognition Surveillance System
This is a project that uses OpenCV, NumPy, YOLOv3, Haar cascade based algorithm to identify objects and people in real-time video and capture screenshots of blacklisted individuals. This system can be used for surveillance purposes and helps to keep track of people in a certain area.

## Installation
Clone the project from this link https://github.com/sweety-sg/Object-detection-in-LIVE-video/tree/sweety
To run the project, you need to have the following libraries installed:

OpenCV (version 4.5.1 or higher)
NumPy (version 1.19.5 or higher)
face_recognition (version 1.3.0 or higher)
YOLOv3 (download from https://pjreddie.com/darknet/yolo/)

To install these libraries, you can use pip:
```
pip install opencv-python numpy
pip install cmake
pip install dlib
pip install face_recognition
```

## File Description
- peopleSurveillance.ipynb : The Jupyter Notebook file containing the code for the system.\
- faces/ : the folder containing faces to people to be learnt by the model.\
- blacklist.names: contain the list of names of people that need to be captured\
- blacklist-captured/ : folder will contain images of people captured after running the code.\
- README.md: The Readme file for the project.

## Setup
- Add pictures of people whose faces you want the model to learn in the faces folder with format {name_of_person).jpg
- Add your input videos in the the folder input-videos.
- Modify the file blacklist.names to add the names of the people you want to track and spot.
- Now specify the path to your input video in the peopleSurveillance.ipynb file in the variable video_path.

## Run
Now you can run the peopleSurveillance.ipynb file in Jupyter Notebook. your output video will be generated in the root directory and you can access the pictures captures of any blacklisted person in blacklist-captured/ folder.

## Future Scope
Some potential areas of improvement for this project are:
- Multi-Camera Support
- Integration with IOT devices
- Mobile App Integration
- Improved Accuracy of Face Recognition
- Integration with Cloud-Based System
- Customizable Alert System
- Expand Object Detection Capabilities.

## References
Girshick, R., Donahue, J., Darrell, T., & Malik, J. (2014). Rich feature hierarchies for accurate object detection and semantic segmentation. Tech report (v5), UC Berkeley.\
Liu, W., Anguelov, D., Erhan, D., Szegedy, C., Reed, S., Fu, C. Y., & Berg, A. C. (2016). SSD: Single Shot MultiBox Detector.\
Redmon, J., Divvala, S., Girshick, R., & Farhadi, A. (2016). You Only Look Once: Unified, Real-Time Object Detection.


