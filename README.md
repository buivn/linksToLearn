# linksToLearn
This repository contains the useful link to learn things in fields\
**CNN**\
Entropy: https://towardsdatascience.com/demystifying-entropy-f2c3221e2550 this link explain the basic understanding of entropy\

Cross-Entropy: https://towardsdatascience.com/demystifying-cross-entropy-e80e3ad54a8 - this link explain about crossEntropy and how to apply to CNN\

Yolov3: https://github.com/AlexeyAB/darknet?fbclid=IwAR0wcLy4kCpYrjVeG35v3oBWDuRRy-nYbJK6ElMOjsOzKhjl49xVr--MeG8\

**Aruco**\
Link https://github.com/pal-robotics/aruco_ros\

**tf Transformation**\
There are frames need to setup as combination between camera and robot.\
1. Camera frame (usually optical one)
2. Robot base frame
3. Gripper frame
4. Aruco frame - Marker\
<a/>
Finally, the transformation matrix between Camera frame and robot base frame are the output of the calculation.\
The Pose determined by GPD has different frame comparing to the gripper frame, thus it needs a transformation between GPD frame and gripper frame.


