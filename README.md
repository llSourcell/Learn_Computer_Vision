# Learn_Computer_Vision
This is the curriculum for "Learn Computer Vision" by Siraj Raval on Youtube

## Course Objective
This is the Curriculum for [this](https://youtu.be/FSe_02FpJas) video on Learn Computer Vision by Siraj Raval on Youtube. After completing this course, start your own startup, do consulting work, or find a full-time job related to Computer Vision.
Remember to believe in your ability to learn. You can learn CV , you will learn CV, and if you stick to it,
eventually you will master it.

## Find a study buddy
Join the #Computer_Vision_curriculum channel in our Slack channel to find one http://wizards.herokuapp.com

## Components each week
- Video Lectures
- Reading Assignments
- Project(s) 

## Course Length
- 8 weeks
- 2-3 Hours of Study per Day

## Tools Used
- Python, OpenCV, Tensorflow 

## Prerequisites

- Learn Python https://www.edx.org/course/introduction-to-python-for-data-science-3
- Calculus http://tutorial.math.lamar.edu/pdf/Calculus_Cheat_Sheet_All.pdf 
- Linear Algebra https://www.souravsengupta.com/cds2016/lectures/Savov_Notes.pdf 

## Part 1: Low Level Vision (image > image)

### Week 1 ( Basic Image Processing Techniques)
- Luminance (Brightness, contrast, gamma, histogram equalization)
- Linear Filtering (enhance image - blur & sharpen, edge detect, image countours, convolution)
- Non Linear Filtering (Median, Bilateral Filter, morphology )
- Color processing (B&W, Saturation, White Balance)
- Dithering (Quantization, Ordered Dither, Floyd-Steinberg)
- Blending (Image pyramids)
- Texture Analysis
- Template Matching (find object in an image)

#### Video Lectures
- https://www.youtube.com/watch?v=-nt80JUNwlw&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=2 videos 1-5 
#### Reading Assignments
- http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf  Sec 3.1.1-2, 3.2 Sec 3.2.3, 4.2 3.3.2-4
#### Project
- Detect an object in an image via the OpenCV Library

### Week 2 (Motion and Optical Flow)
- Motion Analyis
- Optical Flow
#### Video Lectures
- https://www.udacity.com/course/introduction-to-computer-vision--ud810 Udacity lesson 6
- https://www.youtube.com/watch?v=-nt80JUNwlw&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=2 video 8
- https://www.youtube.com/watch?v=wC8hXuHsHAQ&list=PLvqB6_mDBCdlnT84LK_NvbOqcXLlOTR8j&index=6&t=0s 
#### Reading Assignments
- http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf   Sec 10.5 Sec 8.4 (up until 8.4.1)
#### Project
- Track a moving object in a video frame with OpenCV

### Part 2: Mid Level Vision (image > features)

#### Week 3 (Basic Segmentation)
- Segmentation and clustering algorithms like watershed, grabcut
- Interactive segmentation
- Hough transform (detect circles, lines)
- Foreground Extraction

#### Video Lectures
- https://www.youtube.com/watch?v=ZF-3aORwEc0
- https://www.youtube.com/watch?v=3qJej6wgezA
#### Reading Assignments
- Sec Sec 5.2-5.4 http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf   
#### Project
- Segment Lane lines in a road image with OpenCV

#### Week 4 (Fitting)
- Fitting lines and curves
- Robust fitting, RANSAC
- Deformable contours
#### Video Lectures
- Videos 6-7 https://www.youtube.com/watch?v=-nt80JUNwlw&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=2 
#### Reading Assignments
- Sec 4.3.2 5.1.1 http://szeliski.org/Book/drafts/SzeliskiBook_20100903_draft.pdf    
#### Project
- Compute Vanishing Points in a hallway image with OpenCV

### Part 3: Multiple Views

#### Week 5 (Multiple Images)
- Local invariant feature detection and description
- Image transformations and alignment
- Planar homography
- Epipolar geometry and stereo
- Object instance recognition
#### Video Lectures
- https://www.youtube.com/playlist?list=PLyH-5mHPFffFvCCZcbdWXAb_cTy4ZG3Dj 
#### Reading Assignments
- http://vision.cs.utexas.edu/376-spring2018/#Tues_May_1 see the associated readings on this page
#### Project
- Turn a set of images into a 3D Object with OpenCV

#### Week 6 (3D Scenes)
- Stereo Vision, Dense Motion and Tracking;. 3d Objects 
- 3D Scene understanding
- 3D Segmentation and Modeling
#### Video Lectures
- https://www.youtube.com/watch?v=-nt80JUNwlw&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=2 video 9  
- all videos https://www.coursera.org/learn/stereovision-motion-tracking 
#### Reading Assignments
##### Google and read the following papers
- 1. N. Dalal, Histograms of oriented gradients for human detection 
- 2. G. Csurka et al. (Bag of Visual Words - a brilliant representation of cross field research) Visual categorization with bags of keypoints
- 3. S Lazebnik, C Schmid, J Ponce, Beyond bags of features: Spatial pyramid matching for recognizing natural scene categories 
- 4. Jegou et al. Aggregating local image descriptors into compact codes. 
#### Project
- Perform Object Segmentation in a 3D Scene with OpenCV

### Part 4: High Level Vision (Features > Analysis)

#### Week 7 (Object Detection & Classification)
- Object/scene/activity categorization (semantic segmentation)
- Object detection (Non max suppression , sliding windows, Boundary boxes and anchors, counting)
- YOLO and Darknet, region proposal networks 
- Supervised classification algorithms
- Probabilistic models for sequence data
- Visual attributes
- Optical Character Recognition
- Facial Detection
#### Video Lectures
- https://www.youtube.com/watch?v=a-v5_8VGV0A&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=8 10-18 
- my video on YOLO
#### Reading Assignments
- http://vision.cs.utexas.edu/376-spring2018/#Tues_May_1 see the associated readings on this page
#### Project
- Classify a car in an image with Tensorflow

#### Week 8 (Modern Deep Learning)
- Active learning
- Dimensionality reduction
- Non-parametric methods and big data
- U-Net
- Transfer learning
- Avoiding Overfitting 
- GANs

#### Video Lectures
- videos 19-20   https://www.youtube.com/watch?v=a-v5_8VGV0A&list=PLjMXczUzEYcHvw5YYSU92WrY8IwhTuq7p&index=8 
- my video on transfer learning
- Lectures 1-16 Stanford https://www.youtube.com/watch?v=vT1JzLTH4G4&list=PL3FW7Lu3i5JvHM8ljYj-zLfQRF3EO8sYv 
#### Reading Assignments
- http://vision.cs.utexas.edu/376-spring2018/#Tues_May_1 see the associated readings on this page
#### Project
- Build a Generative Adversarial Network to detect faces



