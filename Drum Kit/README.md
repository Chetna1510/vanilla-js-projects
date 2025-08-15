A small Vanilla JavaScript project that lets you play drum sounds using your keyboard or by clicking on the on-screen buttons.

## How it works

Each button on the page corresponds to a keyboard key.
Pressing the key or clicking the button will:
  Play the associated sound clip.
  Add a temporary highlight effect on the button.
  The highlight disappears automatically after the animation ends.

**Steps**

1. Add an event listener to the entire window object that is listening for a keydown event; the function that we will provide as the callback will be defined next.
2. Iterate through the HTML elements and add an event listener to each one that will fire on the transitionend event.
3. Create function (event handler) will fire when the playing class is added to an element and the transition animation completes.
