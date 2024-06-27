<h2 class="c-project-heading--task">Add a colour palette</h2>

--- task ---
➡️ Add a colour palette.
--- /task --- 

Let users choose colours with a click.

Switch to the `style.css` file and create a pen style.

<div class="c-project-code">
--- code ---
---
language: css
line_numbers: true
line_number_start: 12
line_highlights: 19-24
---
.pixel {
  display: table-cell;
  background-color: white;
  width: 40px;
  height: 40px;
}

.pen {
  display: inline-block;
  width: 40px;
  height: 40px;
  border: 2px solid black;
}

--- /code ---
</div>

Switch to the `index.html` file and add a black and white palette.

<div class="c-project-code">
--- code ---
---
language: html
line_numbers: true
line_number_start: 7
line_highlights: 8-11
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

**Test:** Run your code. You should see your palette at the top.

<div class="c-project-callout c-project-callout--debug">

### Debugging

Notice that the styles for the `pen` class end with a semicolon (`;`).

</div>
