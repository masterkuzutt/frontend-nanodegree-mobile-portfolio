# Website Performance Optimization portfolio project

this project is for udacity front-end web developer nanodegree program.

## PageSpeed Score
### Critical Rendering Path
Comments related to this criteria has '[PageSpeed]' on top.
For PageSpeed insight,web pageis running [here](https://masterkuzutt.github.io/frontend-nanodegree-mobile-portfolio/) .


#### Details
##### index.html
* edit webfont to async
* edit styles.css to inline
* edit google analytics to async
* edit imgtag img/profilepic.jpg to .webp
* add mediaquery to  css/print.css link

##### img/profilepic.webp
*  add new file substitute to img/profilepic.jpg

##### iews/images/pizzeria.jpg
*  resize fit to screen width.


## Getting Rid of Jank
### Frame Rate
Comments related to this criteria has '[ChangePizzaSize]' on top.

#### Details
##### views/js/main.js
* delete determinDx()
* simplify changePizzaSizes()

###  Computational Efficiency
Comments related to this criteria has '[ScrollFPS]' on top.

#### Details
##### views/js/main.js
* improve performance of updatePositions()
  * element selection more specific
  * access document.body.scrollTop once
* edit anomymous function for eventListener
  * limit the number of pizza based on screen width,height

##### views/css/styles.css
* add will-change to .mover

##### views/pizza.html
* change #movingPizzas1 class col-md-6 to col-md-12
