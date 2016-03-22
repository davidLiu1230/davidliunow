---
layout: post
title: Detect rotated items in Illustrator
date:   2016-03-21 21:16:21
categories:
---
I've encountered this problem at work where we need to retrieve the rotational value of a photo from an Illustrator file. This applies to any type of item that has a matrix attribute.

Illustrator uses transformation matrices to calculate the transformations of an object. It's basically a 3*3 matrix:

a b u<br />
c d v<br />
x y w<br />

We just need a(or mValueA) and b(or mValueB) to calculate the rotation:

a = cosine(Theta) * scaling_factor<br />
b = sine(Theta) * scaling_factor

where Theta is the rotation value in radian, and scaling factor is how much the item is scaled from the original image. Therefore, we can easily get the tangent value by dividing two numbers above, and derive out the rotation we want. Illustrator scripting operates in radians, so you might also want to convert it to degrees.

Reference: [link](http://www.senocular.com/flash/tutorials/transformmatrix)
