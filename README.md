# css-tricks
# :pushpin: Flexbox notes 

+ **justify-content**`[flex-start, flex-end, center, space-between, space-around]`: aligns the flex elements along the x-axis

+ **align-items**`[flex-start, flex-end, center, baseline, stretch]`: aligns elements flex along the y-axis

+ **align-self**`[flex-start, flex-end, center, baseline, stretch]`: aligns elements flex elements along the y-axis, cancelling the `align-items` value

+ **align-content**`[flex-start, flex-end, center, space-between, space-around, stretch]`: aligns flex container lines when there is more space on the y-axis
+ **flex-direction**`[row(default), row-reverse, column, column-reverse]`: defines x-axis direction

+ **flex-wrap**`[nowrap(default), wrap, wrap-reverse]`: specifies if flex elements are forced to a single line or can be wrapped in multiple lines 

+ **flex-flow**`[<flex-direction> <flex-wrap>]`: abbreviation of `flex-direction` and `flex-wrap`

+ **order**`[<int .,.,-1,0,1,.,.>]`: specifies flex elements order

***

# :triangular_ruler: Grid notes 

+ **grid-column**`[<grid-column-start>/<grid-column-end>]`: abbreviation of `grid-column-start` and `grid-column-end`

  - **grid-column-start**`[<int>, span]`: defines the initial position of an element with respect to the grid columns

  - **grid-column-end**`[<int>, span]`: defines the final position of an element with respect to the grid columns


+ **grid-row**`[<grid-row-start>/<grid-row-end>]`: abbreviation of `grid-row-start` and `grid-row-end`

  - **grid-row-start**`[<int>, span]`: defines the initial position of an element with respect to the grid rows

  - **grid-row-end**`[<int>, span]`: defines the final position of an element with respect to the grid rows
  

+ **grid-area**`[<grid-row-start>/<grid-column-start>/<grid-row-end>/<grid-column-end>]`: abbreviation of `grid-row` and `grid-column`


+ **grid-template**`[rows / columns]`: abbreviation of `grid-template-rows` and `grid-template-columns`

  - **grid-template-columns**`[<length>, <percentage>, max-content, min-content, minmax(min, max), px, fr]`: specifies grid columns size

  - **grid-template-rows**`[<length>, <percentage>, max-content, min-content, minmax(min, max), px, fr]`: specifies grid rows size
  
  
+ **order**`[<int .,.,-1,0,1,.,.>]`: specifies grid elements order

> **_NOTE_**: span only works with positive values

> **[repeat](https://developer.mozilla.org/es/docs/Web/CSS/repeat)**

> **[fr](https://css-tricks.com/introduction-fr-css-unit/)**


