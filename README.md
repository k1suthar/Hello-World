# Hello-World
# changed this file
```python
    from turtle import Turtle, Screen
    from random import randint

    turtle = Turtle()
    screen = Screen()
    turtle.shape("turtle")
    turtle.speed(100)

    R = 255
    G = 255
    B = 0
    turtle.home()

    for i in range(0, 500):

          rr = randint(0, 255)
          gg = randint(0, 255)
          bb = randint(0, 255)
          turtle.stamp()
    #      turtle.colormode(255)
          screen.colormode(255)
          turtle.pencolor((rr,gg,bb))
          screen.bgcolor((randint(0,255), randint(0,255), randint(0,255)))
    #      screen.bgcolor("pink")
          turtle.forward(i)
          turtle.right(120)
          for i in range(0,3):
            turtle.forward(100)
            turtle.right(276)
            turtle.stamp()
```
