# CSS Variables & JS

This page shows how to dynamically update CSS custom properties (variables) using JavaScript. Users can adjust spacing, blur effects, and background color in real-time through intuitive controls.

## Features

Real-time Updates: Changes apply instantly as you move the sliders
Spacing Control: Adjust padding around the image (0-300px)
Blur Effect: Add blur filter to the image (0-25px)
Color Picker: Change the background color behind the image

Steps:

1. The project uses CSS custom properties defined at the :root level for global scope.
2.  It responds to two types of events:

change: When the user releases a slider or changes color
mousemove: For real-time updates while dragging sliders(moving mouse)

3. JavaScript listens for input changes and updates the CSS variables dynamically.