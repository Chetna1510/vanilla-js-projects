
## Clock

Given a web page with an analog clock created with CSS, write the JavaScript necessary to make the clock functional. Make alterations to the CSS as necessary.

## Features

1. Real-time Updates: Clock hands move every second to reflect current time
2. Smooth Animations: CSS transitions with cubic-bezier timing for natural movement
3. Three Distinct Hands:

Hour hand (shortest)
Minute hand (medium)
Second hand (precise movement)

## Steps

1. The HTML file has 3 div elements which correspond with the second, minute, and hour hand on a clock
2. Set the transition CSS property of .hand to all 0.05s; this tells the browser to gradually apply any changes to the element's styling over a 0.05 second period.
3. Set the transition-timing-function CSS property of .hand to whatever function you prefer, or define your own using the cubic-bezier() property value.
4. Declare & define variables for each clock hand and reference the corresponding HTML element.
5. Create a function which will be responsible for calculating the number of degrees that we need to rotate each clock hand by.
6. Update the transform rule for each clock hand to their corresponding updated values.