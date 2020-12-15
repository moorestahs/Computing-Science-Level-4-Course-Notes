---
title: "Graphics"
draft: false
weight: 80
---

## Bit-mapped Graphics

This is the type of graphic that can be created using a __paint__ application.

A __bit-mapped__ graphic is stored as a 2-dimensional array of pixels where each pixel stores the colour of that pixel. Normally you don't see the pixels as you only look at the overall picture.

Look at the illustration below. In the normal view of the dog (left) it is hard to see the individual pixels, but if the image is zoomed in (right) the pixels become more obvious.

![Bitmapped Dog](/bitmapped-graphic-dog.jpg)

Black and white computer graphics are represented in binary by: if the pixel is black then a 1 is stored in a bit, if it is white then a 0 is stored.  

![Bitmapped Graphic](/bitmapped-graphic.png)

## Size of a black and white bitmapped graphic

Each pixel in a black and white bit-mapped graphic is stored in 1-bit of memory. By counting the pixels, you can work out how much memory it takes to store the picture.

A graphic that is 100 pixels by 50 pixels would require:

__100 x 50 x 1 bits = 5000 bits__

(The 1 is there because each pixel is stored as 1 bit in either black or white.) 

## Bit-Depth

Bitmapped colour graphics require more than 1-bit of memory to store a pixel. The number of bits used to store the colour of each pixel is called the bit depth.

+ 8-bit graphics require 8 bits of memory to store the colour of each pixel.
+ 24-bit graphics require 24 bits of memory to store the colour of each pixel.

This would significantly increase the amount of memory required to store a graphic.

The __number of bits used to represent the colour of each pixel__ is called the __bit-depth__.

## Vector Graphics

Vector graphics store a picture by storing each object’s __attributes__.

![Vector graphics](/vector-graphics.png)

Obviously, when stored in the computer each attribute would be stored as a binary number.

There are several common objects that you need to know how they are represented.  These are:
+ Rectangle
+ Ellipse
+ Line
+ Polygon

For each of these you need to know how the attributes of:
+ coordinates (the x,y of different points in the shape)
+ line colour
+ line width
+ fill colour
	