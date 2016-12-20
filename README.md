# ColorReducer

Instructions for executing the ColorReducer.R file

1) We are using two libraries namely 'jpeg' and 'grid' for reading the JPG image file and displaying the original and transformed image respectively.
So we need to one time install the two packages with the following two commands:

install.packages("jpeg")

install.packages("grid")

2) Also, we need to place the source image file in the working directory of R Studio. We can check this details with the following two commands:

getwd()

setwd("path")

3) The target color values are assigned in a sequential list. For example, the 5 target colors with RGB values:

a)	(255, 255, 255)
b)	(0, 0, 0)
c)	(43, 202, 133)
d)	(196, 148, 62)
e)	(113, 17, 214)

will be represented as:

(255, 0, 43, 196, 113, 255, 0, 202, 148, 17, 255, 0, 133, 62, 214) in our list

4) There are some output and statements in the code to recheck the dimensions and the color code of the images.
