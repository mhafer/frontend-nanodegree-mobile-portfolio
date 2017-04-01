## Website Performance Optimization portfolio project



### My Changes

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Download and save all the images
2. Resize and compress the images
3. Moved script tag to the end of the body
4. Base64 Encoded google fonts
5. Minimized the CSS file and added it as inline CSS6. 
6. Added a print.css file with media="print"
7. Added async to js/perfmatters.min.js and minified it
8. Minimized the HTML file

#### Part 2: Optimize Frames per Second in pizza.html

1. Compressed and Resized both pizza and pizzaria
2. Minified bootstrap.css and main.js
3. Inlined style.css in the header tag
4. removed determineDX() from main.js
5. re-wrote changePizzaSizes() (lines 426-453)
  1.declared a newWidth
  2.removed document.getElements from for loop
6. re-wrote updatePositions()
  1.removed document.getElements from for loop
  2.reduced loop to 30 elements
  3.added requestAnimationFrame() at the end
7. Async added to js file
8. media="screen" added toe CSS file	
9. Minimized the HTML file

You can view the project [here](https://mhafer.github.io/frontend-nanodegree-mobile-portfolio/)

### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
