![A screenshot of a webpage with a text block, then an image block and then another text block. Each block is of the same height.](images/three-tiles.PNG)

The code example below will create three tiles of equal height. The text within the tile will be centred on the x and y axis. 

+ `xcenter` places the text in the centre horizontally
+ `ycenter` places the text in the center vertically
+ `tile` sets a fixed height for the `div` content

--- code ---
---
language: HTML
filename: index.html
line_numbers: true
line_number_start: 
line_highlights: 
---
      <section class="wrap">
        <div class="tertiary xcenter ycenter tile">
          <p>Add text here.</p>
        </div>
        <img src="placeholder.png" alt="Description of the image.">
        <div class="tertiary xcenter ycenter tile">
          <p>Add text here.</p>
        </div>
      </section>
--- /code ---