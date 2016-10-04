To run the project:

1. Unzip the file.
2. In terminal, cd to the path of the unzipped file.
3. Run "python -m SimpleHTTPServer 8000"
4. Go to your browser and enter the url "localhost:8000"
5. To see PageSpeed score, go to terminal and run ./ngrok http 8000.
6. Copy the public URL ngrok gives you and run it on PageSpeed Insights.
5. Enjoy!


I made all the following optimizations:

Index.html

1. Added media queries to the stylesheets (such as "print" for print).
2. Moved the CSS from a stylesheet to inline in the head section on the HTML.
3. Moved print and mobile CSS and fonts to deferred-styles at the bottom of the
page, so they won't be render blocking.
4. Made Google analytics javascript loading asynchronous.

Pizza site


1. Changed querySelectorAll to getElementsByClassName.
2. Moved the declaration (the read) of the variable phase to outside the looping
function.
3. Reduced the number of pizzas that are created to 30, as that is how many
pizzas actually show up on the screen.
4. I simplified the algorithms to change the pizza size, by paring down
unnecessary steps.
5. Added backface-visibility and will-change to give the pizzas their own
individual layers.
# opto-moto-izo
