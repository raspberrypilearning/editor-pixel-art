<h2 class="c-project-heading--task">Create the grid</h2>

--- task ---
➡️ Create a grid.
--- /task --- 

Create a table with black borders.

A `<div>` is an invisible box you can style. 

Into the `<body>` of your `index.html` file, add a `<div>` with the ID `art`, so you can style it. 

<div class="c-project-code">
--- code ---
---
language: html
line_numbers: true
line_number_start: 7
line_highlights: 8-10
---
<body>
  <div id="art">

  </div>  
</body>

--- /code ---
</div>

Switch to the `style.css` file and add the styling for the art `<div>`.

<div class="c-project-code">
--- code ---
---
language: css
line_numbers: true
line_number_start: 1
---
#art {
  display: table;
  border-spacing: 1px;
  background-color: black;
  border: 5px solid black;
}

--- /code ---
</div>

**Test:** Run your code to see the table.
