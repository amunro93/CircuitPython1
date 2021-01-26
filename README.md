# CircuitPython
This is my repositorie for coding projects 

## Table of Contents 
* [Getting Started](#Getting-Started)
* [Hello CicuitPython](#Hello-CircutPython) 
* [CiructPython Servo](#CirucitPython-Servo)




## Getting Started 

### Description

This was my first time using CircutPython but I did have some experince with the Metro Express board. My first expriences with CircutPython was pretty positive. I ran into some problems at the start, but I was able to overcome the issues by asking a classmate in one of are breakout rooms and help from Mr.Helmstetter. I was not able to complete any of the assingments in the first week. It was mostly spent just trying to get use to CircutPython. 

## Hello CircuitPython
### Description
In this Assingment I was able to get the Metro Express board working, and I coded a fade between yellow and blue with a built in LED.  

### [[Code]] 

'''python 
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
''' 
    
## CircuitPython Servo 
## CircuitPython LCD
## CircutPython Photointerupter 
## CircutPython Distance Sensor 
