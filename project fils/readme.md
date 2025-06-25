projecte excuitable fils
# Example: Simple butterfly wing shape using Python Turtle
import turtle
import random

t = turtle.Turtle()
t.speed(0)

colors = ["orange", "blue", "yellow", "red", "purple"]

def draw_wing():
    t.begin_fill()
    t.circle(50, 60)
    t.left(120)
    t.circle(50, 60)
    t.end_fill()

for i in range(2):
    t.color(random.choice(colors))
    draw_wing()
    t.right(180)

turtle.done()
