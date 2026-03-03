<h2 class="c-project-heading--task">Style the grid area</h2>

--- task ---

Turn your grid into a neat set of square “pixels”.

--- /task ---

--- task ---

In `style.css`, add styles for `#art`, `.row`, and `.pixel` so the pixels show as white squares inside a black border.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 1-20
---
#art {
  display: table;
  border-spacing: 1px;
  background-color: black;
  border: 5px solid black;
}

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

--- task ---

**Test:** Run your project  — you should see a **3×3** grid of pixel squares.

--- /task ---