<h2 class="c-project-heading--task">Add a palette</h2>

--- task ---

Add a colour palette above your grid so you can choose colours later.

--- /task ---

--- task ---

In `index.html`, add a `palette` div above the `artboard`.

--- /task ---

<div class="c-project-code">

--- code ---
---
language: html
filename: index.html
line_numbers: true
line_number_start: 4
line_highlights: 6-10
---
</head>
<body>
    <div id="palette">
      <div class="pen" data-colour="black" style="background-color: black;"></div>
      <div class="pen" data-colour="white" style="background-color: white;"></div>
      <div class="pen" data-colour="red" style="background-color: red;"></div>
    </div>

  <div id="artboard">
--- /code ---

</div>

--- task ---

**Test:** Run your project — you should see **three squares** above the grid. This is your pallette.

--- /task ---

<div class="c-project-output">

![An 3x3 grid of squares (pixels) with a thick black border and thin inner borders](images/step6.png)

</div>

<div class="c-project-callout c-project-callout--tip">

### Tip

The pixels will only change to red for now.

</div>


