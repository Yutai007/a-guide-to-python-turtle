<h1>A guide to use python turtle

<h1>By: Teen Ninja Turtles (TNT) </h1>

<h1>&copy; Yutai Long, Nolan Zeng & Austin Nguyen</h1>






from turtle import *

from random import randint

# Function takes in a number, fieldSize which determines how long the field is.
def create_field(fieldSize):

  penup()   
  # Hint: if penup lifts up the drawing pen, what does pendown() do?
  goto(-140, 140) 
  # Pay attention to where the arrow moves when you run the code.

  # Remember that for loops help ease repetitve work ... 
  for step in range(fieldSize + 1):

    write(step, align = 'center') # writes the number down
    
    # Write the code that goes here
    
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


speed(0) # Helps speed up the process of creating the field/game

# When this function is called, it creates a playing field

import random
rl = random.randint(10, 20)




create_field(8*rl/20)

bob = Turtle()

bob.color('green')

bob.shape('turtle')

boi = Turtle()

boi.color('blue')

boi.shape('turtle')

banana = Turtle()

banana.color('yellow')

banana.shape('turtle')

bitcoin = Turtle()

bitcoin.color('red')

bitcoin.shape('turtle')

belgian_waffles = Turtle()

belgian_waffles.color('brown')

belgian_waffles.shape('turtle')

# Move the turtles to the start of the race line. 

bob.penup()

bob.goto(-160, 110)

bob.right(360)

bob.pendown()


boi.penup()

boi.goto(-160, 80)

boi.right(360)

boi.pendown()

banana.penup()

banana.goto(-160, 50)

banana.right(360)

banana.pendown()

bitcoin.penup()

bitcoin.goto(-160, 20)

bitcoin.right(360)

bitcoin.pendown()

belgian_waffles.penup()

belgian_waffles.goto(-160, -10)

belgian_waffles.right(360)

belgian_waffles.pendown()




for turn in range((rl*60)):
  
  bob.forward(randint(1*rl/10, 3*rl/10))
  
  boi.forward(randint(1*rl/10, 3*rl/10))
  
  banana.forward(randint(1*rl/10, 3*rl/10))
  
  bitcoin.forward(randint(1*rl/10, 3*rl/10))
  
  belgian_waffles.forward(randint(1*rl/10, 3*rl/10))

