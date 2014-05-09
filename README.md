#Final Project 

Original Project

Super Mario Bros in VHDL

## Proposal

- `Create a system that will` :
    - Be able to take an image of an NES emulator from a laptop screen via VGA
    - Analyze the image and determine the location of an obstacle on screen
    - Determine the appropriate move for Mario to perform
    - Send that command via usb output


## Detailed Tasks and Schedule

- Find a working Super Mario Bros. Rom
- Figure out how to analyze the VGA signal and interpret the colors ( LSN 35)
- Make sure that the data accurately represents the visuals on screen (LSN 35/36)
- Create code to correctly identify an obstacles position relative to Mario (LSN 36/37)
- Create code to determine the proper action to take (Jump or move forward) (LSN 37)
- Be able to interface the FPGA with the USB input on the laptop to actually control Mario (LSN 38)

##Functionality Levels

- Required: Mario is able to successfully jump onto the goomba on the first screen
- B: Mario can make it past the first pit obstacle
- A: Mario finishes level 1-1

##Hardware

- Controller

# New Project

Digital Oscilloscope in VHDL

## Personal Levels of Functionality 
- Required : Get a functioning Oscilloscope in VHDL
- B : Add additional functions
- A : Add Digital Logic Analyzer

I would say I got B and came close to B. We successfully built an oscilloscope, a voltage guage, a logic probe and almost a fully function digital logic analyzer (the analyzer was able to continuously plot out different levels, a 1 or a 0, however it has no memory of them)
Nik Taormina and I worked extensively on the software while John Miller worked extensively on hardware. However, we all helped each other out in each others areas.

## Troubleshooting
- It was difficult to test an oscilloscope without a working ADC. In order to bypass this, we assigned each of the switches to be a bit of the voltage signal that would be coming in from the ADC into the GPIO.
- A lot of bit files were generated to determine the progress of the project and then making minor adjustments to get the desired effects and functinality

## Video
https://www.youtube.com/watch?v=LdPD-mCjqf8&feature=youtu.be
