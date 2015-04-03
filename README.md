(explain stepps taken in optimization)
OPTIMIZATION OF index.html

1) Added ngrok file and set up local server for page speed testing.

2) Added thumbnail version of pizzeria.jpg to index.html, (named pizzeria_s).

3) Minified and inlined style.css and created minified inlined fonts.css from Google Fonts link.

4) Compressed image files profilepic.jpg and pizzeria.jpg.

OPTIMIZATION OF main.js

1) Compressed image file pizzeria.jpg.

2) Moved 'dx' and 'newwidth' calculations out of for loop in changePizzaSizes and selected the first pizza in the array to perform the calculations on instead of performing the same calculation on 100 pizzas for each re-size.

3) Changed for-loop iteration to "Math.round(innerWidth / 73.333)" in the anonymous function in document.addEventListener('DOMContentLoaded' function(){...}).

4) Moved value of calculation out of for-loop in 'updatePositions' and into value "topScroll".
