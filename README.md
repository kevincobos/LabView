# LabView Examples
## Table of Contents
  - [Description](#description)
  - [Examples](#examples)
    - [Traffic Light](#traffic-light)
    - [Decimal to Binary](#decimal-to-binary)
    - [Temperature Converter](#temperature-converter) 
    
## Description  
This repository contains examples of LabView code that I have written.
## Examples  
  

  ## Traffic Light  
This program simulates a traffic light. The user can select between automatic or manual for the lights to change. The program then runs the traffic light simulation. The user can stop the simulation at any time by pushing the stop button.  

  The program running is shown below as a GIF animation and it is divided into two parts:    
- The front panel on the top, showing the user interface being used.  
- The block diagram on the bottom, showing the code being executed.  

Note: The image is a GIF and may take a few seconds to load, depending on your bandwidth.   
![Traffic Light front panel](/main/img/autofrontpanel.gif)  
![Traffic Light diagram panel](/main/img/autodiagrampanel.gif) 
  
  
 ## Decimal to Binary  
This program converts a decimal number to binary. The main program uses a while loop to keep running until the user exits pushing the exit button. The user enters a decimal number, we use a "decimal to binary array" to convert it to a binary, using a "reverse 1D array" is then reversed and the binary equivalent is displayed using a "boolean array".  

| Decimal | Binary   |
| ------- | -------- |
| 1       | 00000001 |
| 2       | 00000010 |
| 4       | 00000100 |
| 10      | 00001010 |
| 32      | 00100000 |
| 64      | 01000000 |
| 100     | 01100100 |  
  
  
The program running is shown below as a GIF animation and it is divided into two parts:    
- The front panel on the top, showing the user interface being used.  
- The block diagram on the bottom, showing the code being executed.  

Note: The image is a GIF and may take a few seconds to load, depending on your bandwidth.  

![Decimal to Binary](/main/img/decimaltobinary.gif)  
  
 ## Temperature Converter  
This program converts a temperature from Fahrenheit to Celsius and vice versa. The user enters a temperature and selects the unit of measurement. The program then converts the temperature to the other unit of measurement. 
To keep the code clean, I used two subVIs to do the math that convert the temperatures. 
  
The program running is shown below as a GIF animation and it is divided into two parts:    
- The front panel on the top, showing the user interface being used.  
- The block diagram on the bottom, showing the code being executed.  

Note: The image is a GIF and may take a few seconds to load, depending on your bandwidth.   
  
  
![Temperature Converter](/main/img/temperatureconversion.gif)   