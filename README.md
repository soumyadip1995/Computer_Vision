## Learn Computer Vision
### Curriculum Length
- 4 weeks

### Week 1
#### Low-level Computer Vision (Basic Image Processing Techniques) 
#### Length- 14-16 hours
**Luminance (Brightness, contrast, gamma, histogram equalization),Linear Filtering (enhance image - blur & sharpen, edge detect, image countours, convolution),Non Linear Filtering (Median, Bilateral Filter, morphology )
Color processing (B&W, Saturation, White Balance), Optical Flow and Motion Tracking, Texture Analysis**
  - [Computer Vision:Algorithms and Applications](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf) by Richard Szeliski. Read the chapters 3.1-Point Operators to 3.3-More Neighbourhood Operators.
  - Read on [Models of Image formation](http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MARBLE/low/fundamentals/models.htm)
  - Read on [Models of Geometric Projection](http://homepages.inf.ed.ac.uk/rbf/CVonline/LOCAL_COPIES/MARBLE/low/fundamentals/geomet.htm)
  - Watch the [videos](https://www.youtube.com/watch?v=-nt80JUNwlw&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=2) 1 to 5 which is an  introductory course on computer vision by University of Washington.
  - Watch the lesson 6 of Udacity's [Introduction to Computer Vision](https://www.udacity.com/course/introduction-to-computer-vision--ud810) course
  - Watch the [video 8](https://www.youtube.com/watch?v=a-v5_8VGV0A&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=8) which is an introductory course on computer vision by University of Washington.
 #### Optical flow, Motion Tracking and Texture Analysis
  - [Computer Vision:Algorithms and Applications](http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf) by Richard Szeliski. Read the chapters 8.4- Optical Flow
  - Watch the lecture on [Optical Flow and Tracking](https://www.youtube.com/watch?v=wC8hXuHsHAQ&list=PLvqB6_mDBCdlnT84LK_NvbOqcXLlOTR8j&index=6&t=0s)
  - [Texture Analyis Lecture](https://courses.cs.washington.edu/courses/cse455/09wi/Lects/lect12.pdf) by University of Washington.
  
#### Assignment
  - Detect an object in an image via the OpenCV Library.
  - Track a moving object in a video frame with OpenCV
  
### Week 2
#### Length- 14-20 hours
#### Image Segmentation, Fitting and Multiple images(Mid-Level Vision Techniques(images>features))
**Basic Image Segmentation(Segmentation and clustering algorithms like watershed, grabcut, Interactive segmentation, Hough line transform,(detect circles, lines)**

  - Watch [DIP Lecture 12a: Image Segmentation](https://www.youtube.com/watch?v=ZF-3aORwEc0) on Image Segmentation
  - Watch the Lecture on [Image Segmentation](https://www.youtube.com/watch?v=3qJej6wgezA) By IIT Kharagpur.
  - Read about [Interactive Foreground Extraction using GrabCut Algorithm](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_grabcut/py_grabcut.html) by OpenCV.
  - Read about [Hough-Line Transform](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_houghlines/py_houghlines.html) and [Image Segmentation By Watershed Algorithm](https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_imgproc/py_watershed/py_watershed.html) by OpenCV.
  
#### Fitting lines and curves, Robust fitting, RANSAC,Deformable contours
   - Watch the [Lecture 6](https://www.youtube.com/watch?v=bn4KHa_zWuQ&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=6) for Features, Matching, and RANSAC and [Lecture 7](https://www.youtube.com/watch?v=taty6lPVcmA&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=7) for Matching, RANSAC, SIFT, and HOG.
#### Multiple Images(Local invariant feature detection and description,Image transformations and alignment,Object instance recognition)
   - Watch the [videos](http://vision.cs.utexas.edu/376-spring2018/#Tues_May_1) by CS376 Computer Vision, Spring 2018
   - Watch the video Lecture series on [Multiple View Geometry in Computer Vision](https://www.youtube.com/playlist?list=PLyH-5mHPFffFvCCZcbdWXAb_cTy4ZG3Dj)
#### Assignment
   - Compute Vanishing Points in a hallway image with OpenCV [here]()
   - Turn a set of images into a 3D Object with OpenCV.
   
### Week 3
#### Length:- 16-20 hours
#### 3D and High Level Vision Techniques( features> analysis)
**Stereo Vision, Dense Motion and Tracking;. 3d Objects, 3D Scene understanding,3D Segmentation, Modeling. Object Detection and Classsification**
 
   - Watch [Lecture 9](https://www.youtube.com/watch?v=AA8FEwutsVk&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=9) for 3D, Depth Perception, and Stereo.
   - Watch the full course [Stereo Vision, Dense Motion & Tracking](https://www.coursera.org/learn/stereovision-motion-tracking) by Coursera.
   - Read the following papers:-
      - S Lazebnik, C Schmid, J Ponce, Beyond bags of features: Spatial pyramid matching for recognizing natural scene categories.
      - Jegou et al. Aggregating local image descriptors into compact codes.
#### Object Detection and Classsification(Object/scene/activity categorization (semantic segmentation),Object detection (Non max suppression , sliding windows, Boundary boxes and anchors, counting),YOLO and Darknet, region proposal networks,Supervised classification algorithms,Probabilistic models for sequence data,Optical Character Recognition,Facial Detection)

   - Watch the video Lectures 10- 18 of [The Ancient Secrets of Computer Vision](https://www.youtube.com/playlist?list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p) 
   - Watch  the full [playlist](https://www.youtube.com/playlist?list=PLZBN9cDu0MSk4IFFnTOIDihvhnHWhAa8W) on YOLOv3 object detection by Ivan Goncharov.
   - Read [Lectures](http://vision.cs.utexas.edu/376-spring2018/#Tues_May_1) by CS376 Computer Vision, Spring 2018

#### Assignments
   - Perform Object Segmentation in a 3D Scene with OpenCV
   - Classify a car in an image with Tensorflow.

### Week 4
#### Length:- 18 hours
#### Deep Learning
**Active learning, Dimensionality reduction, Non-parametric methods and big data, U-Net,Transfer learning,Avoiding Overfitting,GANs**
   
   - Watch the video Lectures 19 and 20 of [The Ancient Secrets of Computer Vision](https://www.youtube.com/playlist?list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p)
   - Watch the video lectures 1-13 of [CS231n](https://www.youtube.com/playlist?list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv) of Stanford University
   - Read the Blog post on [U-net](https://towardsdatascience.com/u-net-b229b32b4a71) on Towards Data Science.
   - Read the paper on [Fully Convolutional Networks for Semantic Segmentation](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf) by UC Berkeley.

#### Assignment
   - Build a Generative Adversarial Network to detect faces
