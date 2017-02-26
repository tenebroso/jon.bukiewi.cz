---
layout: post
title:  "JS30 D16: CSS Text Shadow and Object Destructuring"
date:   2017-02-25 09:48:01 -0600
---

<p data-height="465" data-theme-id="0" data-slug-hash="aJzXNb" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 16 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/aJzXNb/">JavaScript 30: Day 16 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I'm back! Today we focused on some mouseover actions, which calculate text shadow styling depending on the distance in x and y from the top and left of the browser window. 

The calculation says: "When you move the mouse, grab the height and width of the text. Also grab the distance of the cursor from the top and left of the browser window. If when hovering in the browser window, you hover over the child element (text), make sure that you replace the cursor top and left values with the browser top and left distances, PLUS the distance you are mousing over in the object itself."

Whew.

Then, "set a maximum value - a 'walk' - which is used to define how much the text shadow should extend at the outermost point of the browser. For the x shadow movement, take the postion of the cursor, divided by the width of the element times the walk, minus the walk divided by 2. For the y shadow movement, take the position of the cursor, divided by the height of the element times the walk, minus the walk divided by 2."

It's a lot of stuff. Move your cursor above and I think you'll agree that it's a neat effect. I like the idea of dynamically adjusting the CSS of an element based on JS values or user input. 

Another key term from this exercise was that of "[Object Destructuring](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Destructuring_assignment)" in ES6. I hope to dive more into this when I take Wes's ES6 course in the near future.

More tomorrow! I hope!