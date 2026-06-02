<h2 class="c-project-heading--task">Add a palette</h2>

Add a colour palette above your grid so that you can choose colours later.

In `index.html`, add a `palette` `<div>` above the `artboard`.

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

### Tip
<div class="c-project-callout c-project-callout--tip">
For now, the pixels will only change to red.
</div>

## Now run your code

You should see **three squares** above the grid. This is your palette.

<div class="c-project-output">

![Three squares coloured black, white, and red above the 3-by-3 grid of squares.](images/step6.png)

</div>
