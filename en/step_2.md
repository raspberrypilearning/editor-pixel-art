<h2 class="c-project-heading--task">Style the grid area</h2>

In `style.css`, add styles for `#art`, `.row`, and `.pixel`

## Step 1

Click on the file icon, and the `style.css` file.

<div class="c-project-output">
![screenshot](images/css-file.png)
</div>

## Step 2

The pixels show as white squares inside a black border. Experiment with colours, and change the `width` and `height` to get the artboard looking how you want it.

### Tip
<div class="c-project-callout c-project-callout--tip">
You can find more CSS colour names [here](http://jumpto.cc/colours){:target="_blank"}.
</div>

<div class="c-project-code">
--- code ---
---
language: css
filename: style.css
line_numbers: true
line_number_start: 1
line_highlights: 4-5, 15-17
---
#artboard {
  display: table;
  border-spacing: 1px;
  background-color: blue;
  border: 5px solid blue;
}

.row {
  display: table-row;
}

.pixel {
  display: table-cell;
  background-color: white;
  width: 60px;
  height: 60px;
  border: 1px solid blue;
}
--- /code ---

</div>

## Now run your code

You should see your **3×3** grid change with your new size and colours.

<div class="c-project-output">

![An 3x3 grid of squares (pixels) with a thick black border and thin inner borders](images/step3.png)

</div>
