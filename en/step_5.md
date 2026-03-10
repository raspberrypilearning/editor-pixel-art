<h2 class="c-project-heading--task">Change the paint colour</h2>

--- task ---

Change the colour you paint by editing one line of JavaScript.

--- /task ---

--- task ---

In `script.js`, change the colour so pixels paint **red** instead of black.

--- /task ---

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

--- task ---

**Test:** Run your project — click pixels and they should now turn **red**. Experiment with adding other colours.

--- /task ---

<div class="c-project-output">

![An 3x3 grid of squares (pixels) with a thick black border and thin inner borders](images/step5.png)

</div>
