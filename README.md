# Turtle

![Teenage Mutant Ninja Turtles](ninja_turtle.png)

Turtle is a `python` module, it allows you to draw shapes on the screen.
You control a cursor that you can move with the commands:

```python
import turtle

turtle.forward(10) # 10 moves forward
turtle.backward(10) # 10 moves backward
turtle.left(90) # rotates 90 degrees cursor left
turtle.right(90) # clockwise

turtle.penup () # cursor up
turtle.pendown () # cursor down
```

Here is an example of a program drawing a square:

```python
import turtle
turtle.forward (100)
turtle.left (90)
turtle.forward (100)
turtle.left (90)
turtle.forward (100)
turtle.left (90)
turtle.forward (100)
turtle.left (90)
```

# A bit of style

You can customize your designs with different functions:

```python
turtle.speed(speed) # changes the cursor speed
turtle.pensize(size) # changes the size of the line
turtle.pencolor(red, green, blue)
# each component is between 0 and 1
```

# Installation

```shell
sudo apt-get install python python-tk
```
