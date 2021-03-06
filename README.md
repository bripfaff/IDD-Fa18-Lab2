# Make a Digital Timer!
 
## Overview
For this assignment, you are going to 

A) [Solder your LCD panel](#part-a-solder-your-lcd-panel)

B) [Write text to an LCD Panel](#part-b-writing-to-the-lcd) 

c) [Using a time-based digital sensor!](#part-c-using-a-time-based-digital-sensor)

D) [Make your Arduino sing!](#part-d-make-your-arduino-sing)

E) [Make your own timer](#part-e-make-your-own-timer) 
 
## In The Report
Include your responses to the bold questions on your own fork of [this lab report template](https://github.com/FAR-Lab/IDD-Fa18-Lab2). Include snippets of code that explain what you did. Deliverables are due next Tuesday. Post your lab reports as README.md pages on your GitHub, and post a link to that on your main class hub page.

## Part A. Solder your LCD panel

![a relative link](./IMG_2792.JPG)

## Part B. Writing to the LCD
 
**a. What voltage level do you need to power your display?**

4.8-5.2 Volts as seen in the datasheet below.

![a relative link](./Capture.PNG)

**b. What voltage level do you need to power the display backlight?**

3.2V. Do not attach it to the 5.0V as it will ruin the backlight as seen below.

![a relative link](./Capture3.PNG)
   
**c. What was one mistake you made when wiring up the display? How did you fix it?**

Nothing I really didnt make any errors with the instructions given. 


**d. What line of code do you need to change to make it flash your name instead of "Hello World"?**

```
lcd.print("hello, world!");
```
to 
```
lcd.print("Brian");
```
 
**e. Include a copy of your Lowly Multimeter code in your lab write-up.**

[Multimeter code](https://github.com/bripfaff/IDD-Fa18-Lab2/blob/master/my_multimeter.ino)

## Part C. Using a time-based digital sensor

[Rotary Encoder Video](https://youtu.be/78G9kaUlpD0)


## Part D. Make your Arduino sing!

**a. How would you change the code to make the song play twice as fast?**

Change this line of code ``` int noteDuration = 1000 / noteDurations[thisNote]; ```

to ```int noteDuration = 1000 / (noteDurations[thisNote]*2); ```

**b. What song is playing?**

Star Wars

## Part E. Make your own timer

**a. Make a short video showing how your timer works, and what happens when time is up!**


Done in collaboration with Karem Arem: Link to [Beer Chugging Timer](https://www.youtube.com/watch?v=Po7BjSpJiNE)

**b. Post a link to the completed lab report your class hub GitHub repo.**
