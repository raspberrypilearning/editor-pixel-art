<h2 class="c-project-heading--task">Make the grid clickable</h2>

Make pixels change colour when you click them.

## Step 1

Click the file icon and open `script.js`.

<div class="c-project-output">
![screenshot](images/js-file.png)
</div>

## Step 2

Add the code below that finds every `.pixel` and turns it black when clicked.

<div class="c-project-code">

--- code ---
---
language: javascript
filename: script.js
line_numbers: true
line_number_start: 1
line_highlights: 5-13
---
function setPixelColour(pixel) {
  pixel.style.backgroundColor = "black";
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

Click a few pixels and they should turn **black**.

<div class="c-project-output">

![An 3x3 grid of squares (pixels) with a thick black border and thin inner borders](images/step4.png)

</div>
