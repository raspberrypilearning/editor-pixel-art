<h2 class="c-project-heading--task">Choose a palette colour</h2>

Click a square in the palette to choose a colour, then paint pixels using that colour.

Update `script.js` so clicking a pen sets `penColour`, and clicking a pixel uses `penColour`.

<div class="c-project-code">

--- code ---
---
language: javascript
filename: script.js
line_numbers: true
line_number_start: 1
line_highlights: 1, 4, 14-20
---
let penColour = "black";

function setPixelColour(pixel) {
  pixel.style.backgroundColor = penColour;
}

document.addEventListener("DOMContentLoaded", () => {
  const pixels = document.querySelectorAll(".pixel");

  pixels.forEach((pixel) => {
    pixel.addEventListener("click", () => setPixelColour(pixel));
  });

  const pens = document.querySelectorAll(".pen");

  pens.forEach((pen) => {
    pen.addEventListener("click", () => {
      penColour = pen.dataset.colour;
    });
  });
});
--- /code ---

</div>

## Now run your code

Click a pen, then click pixels to paint with that colour.

<div class="c-project-output">

![An 3x3 grid of squares (pixels) with a thick black border and thin inner borders](images/step7.png)

</div>
