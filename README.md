# Description

Here we make a colourful star using turtle graphics in pyhton.


# Turtle graphics

Turtle is a Python feature like a drawing board, which let us command a turtle to draw all over it! We can use many turtle functions which can move the turtle around. Turtle comes into the turtle library. The turtle module can be used in both object-oriented and procedure-oriented ways.

Some commonly used methods are:

1. forward(length): moves the pen in the forward direction by x unit.

2. backward(length): moves the pen in the backward direction by x unit.

3. right(angle): rotate the pen in the clockwise direction by an angle x.

4.left(angle): rotate the pen in the anticlockwise direction by an angle x.

5.penup(): stop drawing of the turtle pen.

6.pendown(): start drawing of the turtle pen.


# Approach 

1. First import turtle module in the idle or editor you are using.

import turtle 

2. Get a screen board on which turtle will draw.

ws=turtle.Screen()

A screen like this will appear:-


3. Define an instance for turtle.

4.For a drawing, a Star executes a loop 5 times.

5.In every iteration move the turtle 100 units forward and move it right 144 degrees.

6.This will make up an angle 36 degrees inside a star.

7. 5 iterations will make up a Star perfectly.
