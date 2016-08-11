# Website Performance Optimization portfolio project

Web performance project to reduce jank and increase Google Page Speed Insights scores.

### Running Application

* Google Page Speed Insights is tested on index.html achieving a score of 90 or higher
* To test, run index.html in your browser or visit [this link](https://mrtpain.github.io/frontend-nanodegree-performance)
* Pizzeria scrolling achieves an average of 60fps
* To Test, run pizza.html in the views folder or in your browser, visit [this link](https://mrtpain.github.io/frontend-nanodegree-performance/views/pizza.html)

### Modifications and Updates for Google Insights

Multiple modifications were made to adjust the score of Google's Page Speed Insights

* CSS and JavaScript files are no longer render blocking.
* Inline CSS was used for site wide styles preventing render blocking files.
* JavaScript files were moved to the bottom of the page before the ending body tag.
* Images were optimized for size and compression.

### Modifying Pizzeria

Navigate to the folder named **Views** to see the pizzeria html, styles, and scripts

* **CSS** holds the pizzeria's style sheets
* **JS** holds the pizzeria's JavaScript files
* **Images** holds pizzeria images
* **pizza.html** is used to view the web page

### Modifications and Updates to the Pizzeria

Multiple modifications were made to adjust the FPS rate of the pizza website.

* The Update Positions function was updated formatted to reduce calculations made on the scroll event listener.
* The number of pizzas is dynamically calculated according to screen size.
* Width and Height of background pizzas is included in CSS rather than populated via JavaScript.
* Request Animation Frame is used to smooth pizza movement on scroll.
* Resizing pizzas now takes less than 5ms.