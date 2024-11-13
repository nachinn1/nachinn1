import turtle

# Initialize the turtle
t = turtle.Turtle()
t.pensize(4)
t.shape("turtle")

# Function to move the turtle to a specific position without drawing
def go(x, y):
    t.penup()
    t.goto(x, y)
    t.pendown()

# Draw the main face
go(86.17, 168.35)
t.seth(223.85)
t.circle(92.62, 28.1)
t.seth(251.95)
t.circle(78.38, 51.57)
t.seth(303.52)
t.circle(44.15, 100.97)
t.seth(44.49)
t.circle(80.90, 49.14)
t.seth(93.63)
t.circle(240.24, 28.78)
t.seth(114.62)
t.circle(79.81, 107.71)
t.seth(237.08)
t.circle(-85.50, 55.88)
t.seth(181.2)
t.circle(90.86, 166.53)
t.seth(328.76)
t.circle(75.33, 96.22)

# Draw the first eye
go(90.27, 62.39)
t.begin_fill()
t.seth(318.45)
t.circle(33.33, 111.44)
t.seth(69.89)
t.circle(119.84, 52.97)
t.seth(160.04)
t.circle(30.13, 69.68)
t.seth(229.72)
t.circle(105.60, 46.4)
t.seth(276.12)
t.circle(48.85, 42.33)
t.end_fill()

# Draw the second eye
go(-70.61, 123.61)
t.begin_fill()
t.seth(41.27)
t.circle(12.29, 101.84)
t.seth(143.11)
t.circle(31.87, 79.18)
t.seth(222.29)
t.circle(12.84, 105.86)
t.seth(328.15)
t.circle(33.22, 73.12)
t.end_fill()

# Function to draw eyes
def ojos(x, y):
    go(x, y)
    t.begin_fill()
    t.seth(35.39)
    t.circle(21.41, 99.61)
    t.seth(135)
    t.circle(8.24, 84.98)
    t.seth(219.98)
    t.circle(22.40, 90.52)
    t.seth(310.49)
    t.circle(8.23, 84.9)
    t.end_fill()

# Draw both eyes
ojos(18.25, 164.85)
ojos(-24.40, 166.22)

# Draw the mouth
go(30.71, 211.68)
t.begin_fill()
t.seth(124.25)
t.circle(18.61, 69.03)
t.seth(193.28)
t.circle(5.75, 145.59)
t.seth(338.87)
t.circle(7.20, 39.99)
t.seth(18.86)
t.circle(-11.24, 49.7)
t.seth(329.16)
t.circle(7.5, 21.95)
t.seth(351.11)
t.circle(3.47, 133.14)
t.end_fill()

# Draw the second part of the mouth
go(-26.16, 208.37)
t.begin_fill()
t.seth(19.01)
t.circle(5.80, 147.94)
t.seth(166.95)
t.circle(18.12, 74.23)
t.seth(241.18)
t.circle(2.75, 103.17)
t.seth(344.35)
t.circle(5.42, 48.74)
t.seth(33.09)
t.circle(-10.03, 52.11)
t.seth(340.98)
t.circle(8.78, 38.02)
t.end_fill()

# Function to draw small circles
def circulos(x, y, diametro):
    go(x, y)
    t.begin_fill()
    t.seth(90)
    
