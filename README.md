# Computer Vision - NTUA (2020-2021)

This repository hosts the **lab projects** and **theoretical problem sets** of the Computer Vision course held by ECE NTUA during the Spring 2021.

- Loyal Friend and Lab Partner: [Christos Dimopoulos](https://github.com/chrisdim)

# Lab Projects

## Lab 1: Interest Point Detection and Feature Extraction in Images

For the code to be small enough, we had to remove the image outputs within the notebooks. The code is structured to simply run it and produce the images (after arranging the directories with the input images a little bit).

- **Part 1: Edge Detection in Grayscale and Real Images**


<p align="center">
  <img width="350" height="350" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/edge_in.jpg?raw=true">
  <img width="355" height="355" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/edge_out.png?raw=true">
</p>


- **Part 2: Interest Point Detection**

<p align="center">
<b>
    Corner Detection
</b>
</p>

<p align="center">
  <img width="335" height="220" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/corner_in.jpg?raw=true">
  <img width="345" height="230" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/corner_out.png?raw=true">
</p>

<p align="center">
<b>
    Blob Detection (Top: Singlescale, Bottom: Multiscale)
</b>
</p>

<p align="center">
  <img width="335" height="220" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/blob2_in.png?raw=true">
  <img width="345" height="225" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/blob2_out.png?raw=true">
</p>

<p align="center">
  <img width="335" height="220" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/blob1_in.jpg?raw=true">
  <img width="345" height="225" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab1/README_imgs/blob1_multi.png?raw=true">
</p>

- **Part 3: Image Matching and Classification using Local Descriptors on Interest Points**


## Lab 2: Optical Flow Estimation and Feature Extraction in Videos for Action Recognition

- **Part 1: Face and hands tracking using Lucas-Kanade Optical Flow Method**

<p align="center">
  <img width="350" height="350"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/lk_method.gif?raw=true">
</p>

- **Part 2: Spacio-Temporal Interest Points Detection and Feature Extraction in Human Action Videos**

<p align="center">
<b>
    Harris Detector
</b>
</p>

<p align="center">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/harris_box.gif?raw=true">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/harris_run.gif?raw=true">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/harris_walk.gif?raw=true">
</p>

<p align="center">
<b>
    Gabor Detector
</b>
</p>

<p align="center">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/gabor_box.gif?raw=true">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/gabor_run.gif?raw=true">
  <img width="270" height="210"  alt="animated" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/labs/lab2/README_imgs/gabor_walk.gif?raw=true">
</p>

## Exercise 3.6: One-Step Metric Rectification for the removal of the projective and affine distortion components

In this optional exercise we were asked to implement a one-step metric rectification algorithm based on [1]. The algorithm gets an image as input that seems as if it was taken from the side. The output is an approximation of the photo, if it was taken from the front.

<p align="center">
  <img width="440" height="260" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/problem_sets/paintings.jpg?raw=true">
</p>
<p align="center">
  <img width="460" height="290" src="https://github.com/d-dimos/computer_vision_ntua/blob/master/problem_sets/rectified.png?raw=true">
</p>

---
[1] Hartley - Zisserman, Multiple View Geometry in Computer Vision, 2nd edition, Cambridge University Press, 2000


