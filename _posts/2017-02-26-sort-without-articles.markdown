---
layout: post
title:  "JS30 D17: Sort an Array without Articles"
date:   2017-02-26 03:03:01 -0600
---

<p data-height="265" data-theme-id="0" data-slug-hash="vxONzQ" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 17 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/vxONzQ/">JavaScript 30: Day 17 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

While there's nothing particularly fancy about the above codepen, today's lesson introduced some basic regex stuff to remove the first "An", "The" or "A" articles from the beginning of a band name during the sort, in order to return the correctly alphabetized list. Before handling this sort in the client, this list lives as an array of band names in random order. The codepen above is the resulting list after the sort is applied.

I particularly liked the explanation of the (a, b) sorting that Wes presented. He talked about a and b representing apples, one in each hand. The bigger or first in order get tossed to the top, then a new apple is grabbed in order to compare it to the original, and so on. This is a good visualization tool for me when using this sort method in the future as I've had trouble wrapping my head around the order in this process.

I also appreciated the explanation of the use of the join method when printing out the list. I hadn't realized that setting an array to innerHTML created a comma separated list of strings by default, so using join at the end of the method chain prevented those commas from being added.

Lastly, there was more ES6 goodness sprinkled in here as we optimized the code - more [arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions) and the introduction (to me) of [implicit returns](https://strongloop.com/strongblog/an-introduction-to-javascript-es6-arrow-functions/). 