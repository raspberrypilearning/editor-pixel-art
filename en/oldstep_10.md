<h2 class="c-project-heading--task">Make the palette interactive</h2>

--- task ---
➡️ Let users choose colours with a click.
--- /task --- 

Switch to the `script.js` file and create the variable `penColour` and sets its value to `'black'` 

<div class="c-project-code">
--- code ---
---
filename: script.js
language: javascript
line_numbers: true
line_number_start: 1
line_highlights: 3-5

---
var penColour = 'black';

--- /code ---
</div>

Create a new function called `setPenColour` with an input of `pen` and change the `setPixelColour` function to use the `penColour` variable instead of `'black'`:

<div class="c-project-code">
--- code ---
---
filename: script.js
language: javascript
line_numbers: true
line_number_start: 1
line_highlights: 7-9
---
var penColour = 'black';

function setPenColour(pen) {
  penColour = pen;
}

function setPixelColour(pixel) {
  pixel.style.backgroundColor = penColour;
}

--- /code ---
</div>

Switch to the `index.html` file and add the calls to the `setPenColour` function.

<div class="c-project-code">
--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 9-10
---
<body>
  <div id="palette">
    <div class="pen" style="background-color:white;" onclick="setPenColour('white')"></div>
    <div class="pen" style="background-color:black;" onclick="setPenColour('black')"></div>
  </div>
  <div id="art">
  <div class = "row">

--- /code ---
</div>

**Test:** Switch the pen colour between black and white and paint some pixels!
