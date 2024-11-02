# Rubik's Cube Solver
Java program utilizing a Swing GUI to find a solution to a given scramble for a Rubik's Cube

## Description
This program is able to find a valid solution to a scrambled Rubik's cube using the beginner's method. While this method
gnerates longer solutions, the beginner's method is easy for beginners to learn intuitively (duh). 

The goal of this project was to create a program which a beginner can use in order to learn how to solve the cube. This is
accomplished by allowing the user to enter parameters for a scrambled cube, whether through a text scramble or by 
inputing each individual color on the cube, and then displaying and animating the cube in a 2D format as it is being solved.

In order to make it easier for the user to learn, the animation can be paused, started, fast-forwarded, and rewinded as one 
wishes; the animation speed can also be adjusted. Finally, the solution being followed is printed; moves yet to be 
performed are printed in a black font and moves already performed are printed in a red font.

## Requirements

* Java SDK 1.8 or later

## Installation
After downloading the zip file, unzip it in your preferred directory. 
In the terminal, navigate into the src folder and run:
```
javac CubeDisplayer.java
java  CubeDisplayer
```

## Usage
Before trying to use this program, I advise you to learn the standard notation for turns and rotations on a Rubik's cube
[here](https://ruwix.com/the-rubiks-cube/notation/).

There are two modes in which solutions can be generated. The first is the default text scramble mode, which allows the user
to input a text scramble or generate a random scramble. The second mode is color selection mode, which allows the user
to input the colors of their scrambled cube and follow through a selection. Modes can be toggled using the menu bar.
The following are images of how each mode looks:
<br><br>

Text Scramble Mode - 
 * Scramble can be entered in the text field
   * Scrambled is applied to a new cube by clicking __APPLY__
   * A random scramble is generated by clicking __RANDOM__
 * Animation can be __started, stopped, rewinded, and fast-forwarded__ using the buttons in the top left
 * The __slider__ allows you to change the animation speed
 * Black text: moves yet to be performed
 * Red text: moves completed
 * Use the menu __Mode Selection__ to toggle between modes
![Text Scramble Mode](/images/Text.jpeg)
<br><br>

Color Input Mode (Color Selection Screen) -
 * Use the combo box to select which side you want to enter the colors for
 * Follow the directions under the combo box and input the colors accordingly
   * *Remember to input colors for all 6 sides!*
 * Colors can be selected using the color palette
 * If you want to reset the inputs for all sides, click __RESET__
 * If you are satisfied with your inputs, click __PROCEED__ to view the solution
![Color Input Mode](/images/ColorInput.jpeg)
<br><br>

Color Input Mode (Solution Screen) -
 * Solution presented in same format as Text Scramble Mode
![Color Input Solution](/images/ColorSolution.jpeg)
