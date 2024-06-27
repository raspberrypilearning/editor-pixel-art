<h2 class="c-project-heading--task">Make the palette interactive</h2>

--- task ---
➡️ Let users choose colours with a click.
--- /task --- 

Switch to the `script.js` file and create the variable `penColour` and sets its value to `'black'` 

<div class="c-project-code">
--- code ---
---
language: javascript
line_numbers: true
line_number_start: 1
---
var penColour = 'black';

function setPixelColour(pixel)
{
  pixel.style.backgroundColor = 'black';
}

--- /code ---
</div>

Create a new function called `setPenColour` with an input of `pen` and change the `setPixelColour` function to use the `penColour` variable instead of `'black'`:

<div class="c-project-code">
--- code ---
---
language: javascript
line_numbers: true
line_number_start: 1
line_highlights: 3-6, 10
---
var penColour = 'black';

function setPenColour(pen)
{
  penColour = pen;
}

function setPixelColour(pixel)
{
  pixel.style.backgroundColor = penColour;
}

--- /code ---
</div>

**Test:** Switch the pen colour between black and white and paint some pixels!

<div class="c-project-callout c-project-callout--tip">

### Tip
You already created calls to the `setPenColour` function in the palette HTML, in the last step.
</div>

<div class="c-project-callout c-project-callout--debug">

### Debugging

Notice there is a semicolon at the end of the first line in the JavaScript code.

</div>