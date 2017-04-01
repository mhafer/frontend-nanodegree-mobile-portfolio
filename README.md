## Website Performance Optimization portfolio project



### My Changes

#### Part 1: Optimize PageSpeed Insights score for index.html

1. Download and save all the images
2. Resize and compress the images
3. Moved script tag to the end of the body
4. Base64 Encoded google fonts
5. Minimized the CSS file and added it as inline CSS. 
6. Added a print.css file with media="print"
7. Added async to js/perfmatters.min.js and minified it
8. Minimized the HTML file

#### Part 2: Optimize Frames per Second in pizza.html

1. Compressed and Resized both pizza and pizzaria
2. Minified bootstrap.css and main.js
3. Inlined style.css in the header tag
4. removed determineDx() from main.js
5. re-wrote changePizzaSizes() (lines 426-453)
  1.declared a newWidth
  2.removed document.getElements from for loop
6. re-wrote updatePositions()
  1.removed document.getElements from for loop
  2.reduced loop to 24 elements
  3.added requestAnimationFrame() at the end
7. Moved JS and CSS to bottom of the body
8. media="screen" added toe CSS file	
9. Minimized the HTML file

You can view the project [here](https://mhafer.github.io/frontend-nanodegree-mobile-portfolio/)

### To run the project locally:

1. Download or clone this git repo to your computer
2. Open Chrome (or any browser) and press Ctrl + o (an 'open' window appears)
3. In that window, navigate to the root directory.
4. Double click index.html to open in your browser

Alternatively, if you have WAMP installed:

1. Download or clone this git repo to your computer
2. Copy or move the whole directory into your www folder on your wamp server
3. Access by typing in the URL localhost/www/frontend-nanodegree-mobile-portfolio/index.html


### Customization with Bootstrap
The portfolio was built on Twitter's <a href="http://getbootstrap.com/">Bootstrap</a> framework. All custom styles are in `dist/css/portfolio.css` in the portfolio repo.

* <a href="http://getbootstrap.com/css/">Bootstrap's CSS Classes</a>
* <a href="http://getbootstrap.com/components/">Bootstrap's Components</a>
