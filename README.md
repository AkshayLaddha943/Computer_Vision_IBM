# Computer_Vision_IBM

A digital image can be interpreted as a rectangular array of numbers. An image is comprised of rectangular grid of blocks called pixels which are denotes as intensity values.

Digital images have an intensity value between 0<=intensity_val<=255

OpenCV differs from PIL in a way that the order of channel arrays is different with PIL having RGB and OpenCV having the order of BGR

## Image Manipulation
Within Image manipulation, we perform -

 * **Flipping images** refers to changing the orientation of the image by interchanging the column and row index values
 * **Cropping images** refers to cutting out part of image and throwing out the rest
 * **Changing Image pixels** refers to changing the intensity values of image

For pixel transformations, we perform -
 * **Histogram** counts the number of occurences of pixels in an image. An example of Histogram -
  The darker portions represent lower intensities and brighter regions are mapped to higher values
 
<p align="center"><img src="https://github.com/AkshayLaddha943/Computer_Vision_IBM/blob/main/Imgs/histogram.PNG" height="250" width="500" alt="header pic"/>
 
 
 * **Intensity Transformation**  changes an image one pixel at a time
 * **Image Negative** reverse the intensity levels of an image
 * **Brightness and contrast adjustments** A linear transform can be seen as applying as brightness and contrast adjustments
 * **Histogram Equalization** is an algorithm that uses image's histogram to adjust the contrast
 * **Thresholding and Image Segmentation** applies threshold to every pixel which can be used to extract objects from image called segmentation
 

## Geometric Operations

Following Geometric operations can be performed - 


 * **Scaling**  reshape, shring or expand the image in a horizontal or vertical direction
 * **Image Negative** reverse the intensity levels of an image 

  
