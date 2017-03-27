## Website Performance Optimization portfolio project


### Getting started


To run this live demo please visit:
https://kunjanpatel1.github.io/frontend-nanodegree-mobile-portfolio/

To run this locally just open index.html in your favorite local browser.

### Optimizations

####Part 1: Optimizations in index.html

1) Added media=print to print.css to stop unnecessary loading of this style sheet
2)Inline style.css
3)Optimized images



####Part 2: Optimizations to main.js/pizz.html

1) Changed all querySelectors to getElementById
2) Updated funciton changePizzaSizes to only calculate new width once rather than calculating for each pizza.
3) Removed recurring search for pizzaDiv in for-loop
4) Removed recurring search for movingPizza element in for-loop
5) Optimized large image

###Results

  With these changes I was able to achieve a page score of
  Mobile: 94
  Desktop: 95
  Resuls Link: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fkunjanpatel1.github.io%2Ffrontend-nanodegree-mobile-portfolio%2Findex.html&tab=desktop
