<h2 class="c-project-heading--task">Make the grid clickable</h2>

Make pixels change colour when you click on them.

## Step 1

Click on the **Project files** icon and open `script.js`.

<div class="c-project-output">
![script.js selected in the 'Project files' menu and open in a tab in the editor.](images/js-file.png)
</div>

## Step 2

Add the code below to find every `.pixel` and turn it black when clicked.

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

Click on a few pixels and they should turn **black**.

<div class="c-project-output">

![Five squares in the 3-by-3 grid of squares are now black.](images/step4.png)

</div>
