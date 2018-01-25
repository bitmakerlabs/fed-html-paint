HTML Paint

Using HTML, CSS and JS, let's create an application that paints blocks into the viewport.

1. Create an event listener for a `mousemove`
2. Create a new element using `document.createElement()` and add to it:
    1. A class of `block`
    2. A `top` value that matches the position of the mouse Y
    3. A `left` value that matches the position of the mouse X
3. Add the element to the `#artboard` using `appendChild()`

Ways to expand this project:

  1. Allow the user to cycle through a selection of `background-color` values to apply to the new block by listening for a `keyUp` of the `spacebar`
      1. What would you need to achieve this? Perhaps an array? Think it through first, then solve.
  2. Set the `background-color` of the `.block` to change on a timer every 1000 milliseconds
      1. Use `setInterval()` to create a timed interval
      2. Setup a `keyUp` event listener to start/stop the timed interval
