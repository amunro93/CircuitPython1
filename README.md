# CircuitPython
This is my repositorie for coding projects 

## Table of Contents 
* [Getting Started](#Getting-Started)
* [Hello CicuitPython](#Hello-CircuitPython) 
* [CirucitPython Servo](#CirucitPython-Servo)
* [CircuitPython LCD](#CircuitPython-LCD)
* [CricuitPython Photointerupter](#CircuitPthyon-Photointerupter)
* [CircuitPython Distance Sensor](#CircuitPython-Distance-Sensor)



## Getting Started 

### Description

This was my first time using CircuitPython, but I did have some experince with the Metro Express board. My first expriences with CircutPython was pretty positive. I ran into some problems at the start, but I was able to overcome the issues by asking a classmate in one of are breakout rooms and help from Mr.Helmstetter. I was not able to complete any of the assingments in the first week. It was mostly spent just trying to get use to CircutPython. 

## Hello CircuitPython
### Description
In this Assingment I was able to get the Metro Express board working, and I coded a fade between yellow and blue with a built in LED.  

### Code 

```python 
import board
import neopixel
import time

dot = neopixel.Neopixel(board.NEOPIXEL, 1)

while True:
    print("Make it blue!")
    dot.fill((0,0,255))
    time.sleep(.5)
    print("make it yellow!")
    dot.fill((255,255,0))
    time.sleep(.3) 
```

### Reflection
I liked how it was a good laerning assingment for CiruitPython and for some people the Metro Express board and also I like how the LED was built into the board. For the first assingment of coding I thought it was good beacuse it got are mind thinking about coding after the long summer break, but it wasn't to hard to make are selves feel deafeted.  
    
## CircuitPython Servo 
### Description
For this assingment I was challenged to make a servo turn from 0 to 180 degrees. I needed two wires one would make the servo turn to 180 degrees the other to 0. I did this last year so that helped but I didn't remember everything.
### Image 
![Servo Wiring](CircuitPythonServoWiring.jpg)
* I got this image from Alden Dent (adent11)
### Code 
### Reflection 
It
## CircuitPython LCD
## CircuitPython Photointerupter 
## CircuitPython Distance Sensor 
