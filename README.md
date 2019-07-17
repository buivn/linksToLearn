# linksToLearn
This repository contains the useful link to learn things in fields\
**CNN**\
Entropy:\
- https://towardsdatascience.com/demystifying-entropy-f2c3221e2550 this link explain the basic understanding of entropy\

Cross-Entropy:\
- https://towardsdatascience.com/demystifying-cross-entropy-e80e3ad54a8 - this link explain about crossEntropy and how to apply to CNN
CNN's Understanding: \
- https://jhui.github.io/2017/03/16/CNN-Convolutional-neural-network/ \
- https://www.youtube.com/watch?v=gZmobeGL0Yg&list=PLZbbT5o_s2xq7LwI2y8_QtvuXZedL6tQU&index=1 
Keras: \
- https://www.youtube.com/watch?v=RznKVRTFkBY&list=PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL \

**Yolov3**\
Link to install and instruction: https://github.com/AlexeyAB/darknet?fbclid=IwAR0wcLy4kCpYrjVeG35v3oBWDuRRy-nYbJK6ElMOjsOzKhjl49xVr--MeG8\ \
Links to Learn Yolo: \
- https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/ \
- https://modelzoo.co/model/keras-yolov3 


**Aruco**\
Link to install: https://github.com/pal-robotics/aruco_ros .\
To run Aruco with only one camera, it requires launch file single.launch. Berore running, some parameters shoud be adjusted as markerSize (dimension of black square), topic names for /camera_info and /image. \
The is a small change in the code: in aruco_ros_utils.cpp file, in line 55, change the if (rotate_marker_axis) by if (false).\
To display aruco_marker_frame, using image_view: rosrun image_view image_view image:=/aruco_single/result


**tf Transformation**\
There are frames need to setup as combination between camera and robot.\
1. Camera frame (usually optical one)
2. Robot base frame
3. Gripper frame
4. Aruco/Marker frame - Marker\
<a/>
Finally, the transformation matrix between Camera frame and robot base frame are the output of the calculation.\

The Pose determined by GPD has different frame comparing to the gripper frame, thus it needs a transformation between GPD frame and gripper frame.

**Check version of multiple packages**\
https://tech.amikelive.com/node-841/command-cheatsheet-checking-versions-of-installed-software-libraries-tools-for-deep-learning-on-ubuntu-16-04/

**Reinforcement Learning**\
https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html?fbclid=IwAR3r7frIxnxDp6YJ7dJBRLAY-BMbmPjKC3kb9UVw3Ztagyfl2182hJgzHHE \

**Math**\
Covariance & Correlation Coefficient \
https://www.statisticshowto.datasciencecentral.com/covariance/ \
Covariance & Correlation Matrix\
https://towardsdatascience.com/let-us-understand-the-correlation-matrix-and-covariance-matrix-d42e6b643c22


