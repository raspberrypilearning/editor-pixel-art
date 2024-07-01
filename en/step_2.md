
<h2 class="c-project-heading--task">Add a row of pixels</h2>

--- task ---
➡️ Add a row of three pixels inside the art div.
--- /task --- 

<div class="c-project-code">
--- code ---
---
filename: index.html
language: html
line_numbers: true
line_number_start: 7
line_highlights: 9-13
---
<body>
  <div id="art">
    <div class = "row">
      <div class="pixel"></div>
      <div class="pixel"></div>
      <div class="pixel"></div>
    </div>
  </div>  
</body>

--- /code ---
</div>

Switch to the `style.css` file and add the styles for rows and pixels:

<div class="c-project-code">
--- code ---
---
filename: style.css
language: css
line_numbers: true
line_number_start: 8
---
.row {
  display: table-row;
}

.pixel {
  display: table-cell;
  background-color: white;
  width: 40px;
  height: 40px;
  border: 1px solid black;
}

--- /code ---
</div>

<div class="c-project-callout c-project-callout--tip">

### Tip
You have used a class instead of an ID to style the row and pixel divs. This is because there will be lots of them.
</div>

**Test:** Run your code to see the row of pixels.

![A row of three squares (pixels) with a thick black border and thin inner borders](images/row-of-three.png)
