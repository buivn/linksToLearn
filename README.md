# linksToLearn
This repository contains the useful link to learn things in fields\
**CNN**\
Entropy:
- https://towardsdatascience.com/demystifying-entropy-f2c3221e2550 
this link explain the basic understanding of entropy\

Cross-Entropy:
- https://towardsdatascience.com/demystifying-cross-entropy-e80e3ad54a8 
- this link explain about crossEntropy and how to apply to CNN
<p>
CNN's Understanding: 
- https://jhui.github.io/2017/03/16/CNN-Convolutional-neural-network/ \
- https://www.youtube.com/watch?v=gZmobeGL0Yg&list=PLZbbT5o_s2xq7LwI2y8_QtvuXZedL6tQU&index=1 
<p>
Keras: 
- https://www.youtube.com/watch?v=RznKVRTFkBY&list=PLZbbT5o_s2xrwRnXk_yCPtnqqo4_u2YGL \
<p>
Cross-Entroy Loss:
  - https://gombru.github.io/2018/05/23/cross_entropy_loss/ \

**Yolov3**\
Link to install and instruction: https://github.com/AlexeyAB/darknet?fbclid=IwAR0wcLy4kCpYrjVeG35v3oBWDuRRy-nYbJK6ElMOjsOzKhjl49xVr--MeG8\ \
Links to Learn Yolo: \
- https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/ \
- https://modelzoo.co/model/keras-yolov3 


**Aruco**\
Link to install: https://github.com/pal-robotics/aruco_ros .\
To run Aruco with only one camera, it requires launch file single.launch. Berore running, some parameters shoud be adjusted as markerID (26), markerSize (dimension of black square = 0.14m), topic names for */camera_info (/camera_remote/rgb/camera_info)* and */image (/camera_remote/rgb/image_rect_color)*. \
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
Basic understanding: 
- https://spinningup.openai.com/en/latest/spinningup/rl_intro3.html?fbclid=IwAR3r7frIxnxDp6YJ7dJBRLAY-BMbmPjKC3kb9UVw3Ztagyfl2182hJgzHHE 
- https://lilianweng.github.io/lil-log/2018/04/08/policy-gradient-algorithms.html
<p>
Some papers: 

- https://hadovanhasselt.files.wordpress.com/2015/12/rl_in_continuous_spaces.pdf \
- http://users.cecs.anu.edu.au/~rsl/rsl_papers/99ai.kambara.pdf \
- https://vmayoral.github.io/robots,/ai,/deep/learning,/rl,/reinforcement/learning/2016/07/06/rl-intro/ \
- https://medium.com/@asteinbach/rl-introduction-simple-actor-critic-for-continuous-actions-4e22afb712


**Math**\
Covariance & Correlation Coefficient \
https://www.statisticshowto.datasciencecentral.com/covariance/ \
Covariance & Correlation Matrix\
https://towardsdatascience.com/let-us-understand-the-correlation-matrix-and-covariance-matrix-d42e6b643c22

**Support Vector Machine**\
https://towardsdatascience.com/support-vector-machine-introduction-to-machine-learning-algorithms-934a444fca47 \
\
https://towardsdatascience.com/support-vector-machines-soft-margin-formulation-and-kernel-trick-4c9729dc8efe \
https://towardsdatascience.com/support-vector-machines-soft-margin-formulation-and-kernel-trick-4c9729dc8efe \

**Plot a curve and points**\
https://www.desmos.com/calculator/n6uwzixrmu \
**Motion Planning** \
https://www.mathworks.com/help/nav/ug/motion-planning-with-rrt-for-manipulators.html \
http://planning.cs.uiuc.edu/ \
https://parasol.tamu.edu/groups/amatogroup/research/motionPlanning.php \

**PCLVisuallizer** \
To show line, normal vector, points, circle, ....
http://pointclouds.org/documentation/tutorials/pcl_visualizer.php \

**Github**
- Installing Github Desktop: https://linuxtechlab.com/how-to-install-github-on-ubuntu-step-by-step/ \
- To clone a repo from Github to Github Desktop: *git clone git@github.com:buivn/packg-needed* \
- To remove a folder of Github Desktop: *git rm -r folder-name* \
- To add a new files, folder, update files: *git add .* \
- Then commit: *git commit -m "explain"* \
- Then push back github account: *git push origin desired-branch* \
Sometimes, you need to use *git pull* \

**ROS CMakeLists.txt** \
https://github.com/cse481sp17/cse481c/wiki/Lab-30:-Introduction-to-point-cloud-processing \


**OS, shell Scripts, Shell**\
http://linuxcommand.org/lc3_writing_shell_scripts.php \


Smoother - spline interpolation

