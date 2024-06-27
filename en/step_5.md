<h2 class="c-project-heading--task">Colour the pixels</h2>

--- task ---
➡️ Colour the pixels.
--- /task --- 

Use JavaScript code to colour a pixel when you click it.

Switch to the `script.js` file and create the function `setPixelColour`. 

A pixel is passed to the function, so the function can change that pixel’s colour.

<div class="c-project-code">
--- code ---
---
language: js
line_numbers: true
line_number_start: 1
---
function setPixelColour(pixel)
{
  pixel.style.backgroundColor = 'black';
}

--- /code ---
</div>

Switch to the `index.html` file and add an `onclick` event.

<div class="c-project-code">
--- code ---
---
language: html
line_numbers: true
line_number_start: 7
line_highlights: 10
---
<body>
  <div id="art">
    <div class = "row">
      <div class="pixel" onclick="setPixelColour(this)"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip
The `this` in brackets is passed to the `setPixelColour` function, so it knows which pixel to colour — ***this*** pixel!
</div>

**Test:** Run your code and click on the first pixel. It should turn black.

<div class="c-project-callout c-project-callout--debug">

### Debugging

Notice that `backgroundColor` in the JavaScript code uses the American spelling of ‘colour’.

</div>
