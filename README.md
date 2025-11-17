
import turtle

# تنظیمات اولیه
screen = turtle.Screen()
screen.title("گرافیک کامپیوتری با Turtle")
screen.bgcolor("white")

# ایجاد یک لاک‌پشت
t = turtle.Turtle()
t.color("blue")
t.pensize(3)

# رسم مثلث
for _ in range(3):
    t.forward(100)  # حرکت به جلو
    t.left(120)     # چرخش به چپ

# پایان کار
turtle.done()