
import turtle

screen = turtle.Screen()
screen.title("Turtle")
screen.bgcolor("white")

t = turtle.Turtle()
t.color("blue")
t.pensize(3)

for _ in range(3):
    t.forward(100) #  
    t.left(120)     # 

turtle.done()