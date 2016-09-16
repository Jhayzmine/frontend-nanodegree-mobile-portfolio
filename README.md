# Website Performance Optimization portfolio project

###Steps to run application:

1. open index.html in your browser
2. visit Cam's Pizzeria link
3. look at all the yummy pizzas and notice how amazing everything runs


###Steps I took to optimize front page (index.html):

1. Removed Google fonts
2. Inlined CSS
3. moved JS to bottom and added async to perfmatters and google analytics
4. minfied CSS, HTML, and JS
5. Compressed images as needed

###Steps I took to optimize Cam's Pizzeria page (views/js/main.js):

1. In function changePizzaSizes: changed querySelectorAll to getElementsByClassName and pulled var out of for loop
2. Removed dx function and change to use sizeSwitcher
3. In function updatePositions: changed querySelectorAll to getElementsByClassName, created variable for document.body.scrollTop and pulled out of for loop


###For tools I use the latest version of Dreamweaver and Photoshop.