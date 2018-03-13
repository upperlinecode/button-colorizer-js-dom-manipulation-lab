# Color Buttons!

## Setup

This lab is already half-built. The buttons are on the page as divs, and there's already some responsiveness built in to the first button. Go ahead: open up the preview of the index, then open up the JavaScript Terminal, and then see what happens when you click on the red button. 

## Level 1: Console Log Statements

Practice selecting the other two buttons and adding an event listener to each one of them. To pass level 1, each one of the existing buttons should log the color you pressed to the console. 

## Level 2: Modify Style 

Console log statements are cool, but only cool developers like us can see them. Let's make the results visible by changing the background color of the resultbox to match the button you pressed. 

Make this work for all three colors. 

<details>
  <summary>Stuck? Click here for a hint.</summary>
  First, make sure you select the resultbox div and store it in a variable so you can reference it inside your event listeners.
  Second, remember the code to manipulate style is `.style.backgroundColor = "red"` -- the .style method will let you manipulate most of the same properties as you can in CSS, but remember to use camelCase (like backgroundColor) in JavaScript instead of the hyphenation (like background-color) that we use in CSS.
</details>

## Level 3: Events

Right now, your colors change when you click on the events. Try some of these:
* "mousover"
* "mouseout"
* "mousemove"
* "dblclick"


# Extensions
For an extra challenge, try some of the following:
* Make a reset button div in the html and have it change the color back to white.
* Use an `rgb(red, green, blue)` color declaration instead of a color name to declare the style. 
* Make it so that clicking a color doesn't just reset the color - it adds to the color, so clicking red and then blue (or blue then red) will actually paint it purple or magenta
    * FYI, one good purple/magenta declaration is `rgb(255, 0, 255)`.
    * It may be helpful to store color values in variables like r, g, and b - that way the colors are accessible across multiple different event listener functions.
* Make it so that there are two of each color button - one that increases the amount of that color, and one that decreases the amount of that color.    