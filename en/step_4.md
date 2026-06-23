<h2 class="c-project-heading--task">Change the paint colour</h2>

To change the colour you paint, edit one line of JavaScript.

In `script.js`, change the colour so that pixels are painted **red** instead of black.

<div class="c-project-code">

--- code ---
---
language: javascript
filename: script.js
line_numbers: true
line_number_start: 1
line_highlights: 2
---
function setPixelColour(pixel) {
  pixel.style.backgroundColor = "red";
}

document.addEventListener("DOMContentLoaded", () => {
  const pixels = document.querySelectorAll(".pixel");

  pixels.forEach((pixel) => {
    pixel.addEventListener("click", () => setPixelColour(pixel));
  });
});
--- /code ---

</div>

## Now run your code

Click on pixels and they should now turn **red**. Experiment with adding other colours.

<div class="c-project-output">

![The five squares in the 3-by-3 grid of squares that were black in the last step are now red.](images/step5.png)

</div>
