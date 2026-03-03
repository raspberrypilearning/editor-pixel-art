<h2 class="c-project-heading--task">Add a palette</h2>

--- task ---
Add colour pens above your grid so you can choose colours later.
--- /task ---

--- task ---
In `index.html`, add a `palette` div above `#art` and create a few pens using `data-colour`.
--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 1
line_highlights: 11-17
---
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
  </head>

  <body>
    <h1>Pixel Art</h1>

    <div id="palette">
      <div class="pen" data-colour="black" style="background-color: black;"></div>
      <div class="pen" data-colour="white" style="background-color: white;"></div>
      <div class="pen" data-colour="red" style="background-color: red;"></div>
    </div>

    <div id="art">
    
  </body>
</html>
--- /code ---

</div>

--- task ---
**Test:** Run your project — you should see **three pen squares** above the grid. 
--- /task ---