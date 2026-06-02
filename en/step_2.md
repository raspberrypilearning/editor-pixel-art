<h2 class="c-project-heading--task">Style the grid</h2>

In `style.css`, add styles for `#artboard`, `.row`, and `.pixel`.

## Step 1

Click on the **Project files** icon, then the `style.css` file.

<div class="c-project-output">
![style.css selected in the 'Project files' menu and open in a tab in the editor.](images/css-file.png)
</div>

## Step 2

The pixels show as white squares inside a black border. Experiment with colours, and change the `width` and `height` to get the artboard to look how you want it to.

### Tip
<div class="c-project-callout c-project-callout--tip">
You can find [more CSS colour names here](http://jumpto.cc/colours){:target="_blank"}.
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

You should see your **3×3** grid change with your new sizes and colours.

<div class="c-project-output">

![A larger 3-by-3 grid of squares with a thick blue outer border and thin blue internal lines.](images/step3.png)

</div>
