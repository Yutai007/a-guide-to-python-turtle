<center>


<h1>A guide to use python turtle

<h1>By: Teen Ninja Turtles (TNT) </h1>

<h1>&copy; Yutai Long, Nolan Zeng & Austin Nguyen</h1>






from turtle import *
<br>
from random import randint
<br>
# Function takes in a number, fieldSize which determines how long the field is.
<br>
def create_field(fieldSize):
<br>
  penup()   
  <br>
  # Hint: if penup lifts up the drawing pen, what does pendown() do?
  <br>
  goto(-140, 140) 
  <br>
  # Pay attention to where the arrow moves when you run the code.
<br>
  # Remember that for loops help ease repetitve work ... 
<br> 
  for step in range(fieldSize + 1):
<br>
    write(step, align = 'center') # writes the number down
    <br>
    # Write the code that goes here
    <br>
    right(90)
    penup()
    forward(10) 
    pendown()
    forward(10)
    penup()
    forward(10)
    pendown()
    forward(10)
    penup()
    forward(10) 
    pendown()
    forward(10)
    penup()
    forward(10)
    pendown()
    forward(10)
    penup()
    forward(10) 
    pendown()
    forward(10)
    penup()
    forward(10)
    pendown()
    forward(10)
    penup()
    forward(10) 
    pendown()
    forward(10)
    penup()
    forward(10)
    pendown()
    forward(10)
    penup()
    backward(160)
    penup()
    left(90)
    forward(20)

<br>
speed(0) # Helps speed up the process of creating the field/game
<br>
# When this function is called, it creates a playing field
<br>
import random
<br>
rl = random.randint(10, 20)




<br>
create_field(8*rl/20)

<br>
bob = Turtle()
<br>
bob.color('green')
<br>
bob.shape('turtle')
<br>
boi = Turtle()
<br>
boi.color('blue')
<br>
boi.shape('turtle')
<br>
banana = Turtle()
<br>
banana.color('yellow')
<br>
banana.shape('turtle')
<br>
bitcoin = Turtle()
<br>
bitcoin.color('red')
<br>
bitcoin.shape('turtle')
<br>
belgian_waffles = Turtle()
<br>
belgian_waffles.color('brown')
<br>
belgian_waffles.shape('turtle')
<br>
# Move the turtles to the start of the race line. 
<br>
bob.penup()
<br>
bob.goto(-160, 110)
<br>
bob.right(360)
<br>
bob.pendown()
<br>

boi.penup()
<br>
boi.goto(-160, 80)
<br>
boi.right(360)
<br>
boi.pendown()
<br>
banana.penup()
<br>
banana.goto(-160, 50)
<br>
banana.right(360)
<br>
banana.pendown()
<br>
bitcoin.penup()
<br>
bitcoin.goto(-160, 20)
<br>
bitcoin.right(360)
<br>
bitcoin.pendown()
<br>
belgian_waffles.penup()
<br>
belgian_waffles.goto(-160, -10)
<br>
belgian_waffles.right(360)
<br>
belgian_waffles.pendown()
<br>



for turn in range((rl*60)):
  <br>  
  bob.forward(randint(1*rl/10, 3*rl/10))
  <br>
  boi.forward(randint(1*rl/10, 3*rl/10))
  <br>
  banana.forward(randint(1*rl/10, 3*rl/10))
  <br>
  bitcoin.forward(randint(1*rl/10, 3*rl/10))
  <br>
  belgian_waffles.forward(randint(1*rl/10, 3*rl/10))
<br>

