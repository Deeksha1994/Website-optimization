## Website Performance Optimization portfolio project - Project 4

### Instructions
To view the portfolio website download all the files and open index.html in your browser.

To view the pizza website download all of the files and open views/pizza.html in your browser.

1. Images are also optimized to give user a better experience. 

2. Changed all instances of querySelector to getElementById and getElementByClassName depending on whether a class or id is needed.

3. Moved the document.body request out of for loop in the changePizzaSizes and updatePositions functions. This prevents the browser from rendering every time the loop iterates.

4. The needed DOM elements are cached so that the brower doesn't query the DOM every time the for loops are iterated in the updatePositions and changePizzaSizes funcitons.

5. Modified the code to calculate the number of pizzas needed to fill the webpage based on browser inner dimensions.

You can also view the site on github pages by using the links below.

To view the portfolio site on github pages go to https://deeksha1994.github.io/WebsiteOptimization/

To view the pizza site on github pages go to https://deeksha1994.github.io/WebsiteOptimization/views/pizza.html