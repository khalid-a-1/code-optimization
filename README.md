# CS 281: Intro to Computer Systems

## Code Optimization Homework

#### Introduction

This assignment deals with optimizing memory intensive code. Image processing offers many examples of
functions that can benefit from optimization. In this lab, we will consider two image processing operations:
rotate, which rotates an image counter-clockwise by 90◦, and smooth, which “smooths” or “blurs” an
image.

For this lab, we will consider an image to be represented as a two-dimensional matrix M, where Mi,j
denotes the value of (i, j)th pixel of M. Pixel values are triples of red, green, and blue (RGB) values. We
will only consider square images. Let N denote the number of rows (or columns) of an image. Rows and
columns are numbered, in C-style, from 0 to N − 1.

# For more information, read perflab.pdf
