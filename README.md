# Playing with Python Turtle

![Teenage Mutant Ninja Turtles](ninja_turtles.png)

Turtle is a `python` module, it allows you to draw shapes on the screen.
You control a cursor that you can move with the commands:

```python
import turtle

turtle.forward(10) # 10 moves forward
turtle.backward(10) # 10 moves backward
turtle.left(90) # rotates 90 degrees cursor left
turtle.right(90) # clockwise

turtle.penup() # cursor up
turtle.pendown() # cursor down
```

Here is an example of a program drawing a square:

```python
import turtle
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
turtle.forward(100)
turtle.left(90)
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

# To go further

[WikiBook - /Une tortue qui accélère la résolution de problèmes](https://fr.wikibooks.org/wiki/Math%C3%A9matiques_avec_Python_et_Ruby/Une_tortue_qui_acc%C3%A9l%C3%A8re_la_r%C3%A9solution_de_probl%C3%A8mes)
