# Classical Computer Vision assignments done as part of the course CMSC733
## Assignment 1: 
  - <b>Hybrid Image</font></b>: Superposing a low-frequency component of an image & a high-frequency component of another image allows you to see both the images at once.
  - <b>Image Pyramids</b>: Gaussian & Laplacian pyramids enable multi-scale representation of images. They have many applications in image blending, editing & texture synthesis.
  - <b>Edge Detection</b>: Gradient-based edge detector is coded from scratch.
  - <b>Template Matching</b>: A SSD (Sum of Squared Differences) based template matching algorithm is implemented.

## Assignment 2:
  - <span style="font-size:20px;"><b>Feature Detection & Tracking</b>:</span> Implemented a Harris operator based corner detector followed by Non-maxima Suppression to select a few good keypoints & used the Kanade-Lucas-Tomasi procedure to track the movement of those keypoints in a video.
  - <b>Shape Alignment</b>: Given two shape outlines (masks) of similar objects, Iterative Closest Point Algorithm is used to find a transformation matrix between them.
  - <span style="font-size:20px;"><b>Object Instance Recognition</b>:</span> Using SIFT-features of keypoints in 2 images Lowe-style object instance recognition is implemented.

## Assignment 3:
  - <span style="font-size:20px;"><b>[Epipolar Geometry](https://github.com/sparsh-b/CMSC733/blob/master/Epipolar_Geometry.ipynb)</b>:</span> Given a pair of stereo images, estimated homography matrix between them using the normalized 8-point algorithm and calculated the corresponding epipolar lines for various points.
  - <span style="font-size:20px;"><b>Image Stitching</b>:</span> Given a set of overlapping images, detect the repeating keypoints in a successive pair of images & calculate the Fundamental Matrix between the 2 images using RANSAC & normalized 8-point algorithm & finally combine the 2 images.
  - <span style="font-size:20px;"><b>Affine Structure from Motion</b>:</span> Given a sequence of images with camera movement involving only affine transformations, recover the 3D structure of the scene.

## Assignment 4:
  - <span style="font-size:20px;"><b>SLIC Super-pixel Segmentation</b>:</span> Implemented the [SLIC](www.kev-smith.com/papers/SMITH_TPAMI12.pdf) super-pixel segmentation algorithm from scratch.
  - <b>Graph-cut Segmentation</b>: Implemented Graph-cut segmentation using OpenCV.
