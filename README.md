(explain stepps taken in optimization)
OPTIMIZATION OF index.html

1) Added ngrok file and set up local server for page speed testing.

2) Added thumbnail version of pizzeria.jpg to index.html, (named pizzeria_s).

3) Minified and inlined style.css and created minified inlined fonts.css from Google Fonts link.

4) Compressed image files profilepic.jpg and pizzeria.jpg.

OPTIMIZATION OF main.js

1) Compressed image file pizzeria.jpg. Changed for-loop in 'uppdatePositions' to iterate ofer 50 items instead of 'items.length'.

2) Changed for-loop iteration to 100 in the anonymous function in document.addEventListener('DOMContentLoaded' function(){...}).

3) Moved 'dx' and 'newwidth' calculations out of for loop in changePizzaSizes and selected the first pizza in the array to perform the calculations on instead of performing the same calculation on 100 pizzas for each re-size.