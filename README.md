# Image-Processing

In this notebook we will test some mean-, median- and gaussian-filtering.

The link to my explanations and my tutorial video: https://www.youtube.com/watch?v=79c4srGp-Pk&lc=z233vbrp0mveermqu04t1aokg3vc25ayx4cmh3pipq4nrk0h00410

FILTERS: 
The filtering is done by a simple sliding-window spatial filter 
that replaces the center value in the window with a new value 
(depending on the filter). The window, or kernel, is usually 
square but can be any shape.

MEAN filter: 
Takes the average (mean) of all the pixel values in the window. 

Median filter: 
Takes the median value of all the pixel values in the window. 

GAUSSIAN filter:
It represents the shape of a Gaussian bell-shaped hump. The weights are decreaseing the further away form the center of the kernel we go.
