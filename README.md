# MCG_GFX_Framework_v2
 Light weight graphics library for drawing shapes.
 
## The project
This software is part of my uni corse to create a c++ application to draw a circle, triangle and perform a matrix transformation using a lightweight graphics library that only draws 1 pixel to the screen.
 
## Functions
Here are some of the current functions and how to use them.

### drawLine
drawLine allows the user to draw a line between 2 specified points in a 2d space.\
The function can be used by calling drawLine(x1, y1, x2, y2) where x1, y1, x2 and y2 would be replace with the coordinates of the two points.\

### drawTriangle
drawTriangle allows the user to draw one of the 4 types of triangles at a specified point.\
The fuction can be used by calling drawTriangle(x, y, type) where x and y would specify the bottom left most corner of the triangle and type would be the type of triangle.\
The current types of triangles and their codes are:\
1 = right-angle triangle\
2 = equalatral triangle\
3 = isosceles triangle\
4 = scalene triangle
