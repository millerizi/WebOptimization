Before Changes- Mobile 28/100   Desktop 30/100
1- Added CSS Information to Index.html and removed link to style.css file
2- Added asynch to google analytics Java Script
3- Added media="Print" so the print style sheet is not looked at unless printing.
4- Used Kraken to minize profile pic and pizzaria picture
5- Turned on GZIP in XAMPP config file for Apache server
After Changes Above- Mobile 95/100 Desktop 97/100



The following changes where made to fix the low FPS and produce a consistent 60FPS frame rate when scrolling the page:

1- Found var adjectives noise was incorrect updated to noisy
2- changed the number to 31 for document.addEventListenter instead of max 200 when counting.
3- Created new variable in the updatePosition called top, and then used that for the var phase calculation.
FPS says 60.1 after these changes.

Resize Pizza Change for Slider
1- Removed Height and width so and ussed window.requestAnimationFram(updatePositions);
2- Moved determineDx function call inside the changePizzaSizes function out of the loop. Selected only the first .randomPizzaContainer in the document.
3- moved newwidth out of loop since its the same for all elements, instead of looping through each one.

minified the main.js file and made the pizza.html point to that file.

Refernces:
http://jscompress.com/
http://www.willpeavy.com/minifier/
