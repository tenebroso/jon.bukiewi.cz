---
layout: post
title:  "JavaScript 30: Day 2"
date:   2016-12-13 6:55:49 -0600
categories: javascript30 frontend
---
Day 2 is in the books. Today, with the help of Wes' great tutorial, I built a CSS/JS-based [clock](http://codepen.io/tenebroso/pen/PbyOVg?editors=0010) using a bit of math, the global Date() object and some CSS transforms. In order to add to the affect a bit, I found an SVG clock face and went ahead and dropped it in behind everything and voila. I think it turned out pretty nicely and am again really happy with how well Wes breaks down the pieces as he goes through each day.

<p data-height="600" data-theme-id="0" data-slug-hash="PbyOVg" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 2 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/PbyOVg/">JavaScript 30: Day 2 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

Things I learned:

- transform-origin is a pretty great way to adjust the point at which a rotation occurs on an element. I'm not sure why I haven't encountered this before, but it's never really been on my radar in any of the designs I've worked with. transform-origin was the only way to get the hands of the clock to spin from the center of the clock, rather than spinning on their own center axis. This was achieved by setting transform-origin to 100%. I'll need to keep vendor prefixes in mind for client work through autoprefixer or something manual, but otherwise it's a good tool. 

- I've been opting to use MomentJS on most projects as the default, much like jQuery. It was interesting to explore what capabilities are built into the Date() object besides just *getting* the current date, such as getSeconds, getMinutes, etc. I'm really excited moving forward to see how far I can get without jQuery and now without MomentJS. These are both awesome tools, but I will be the first to admit that they are easy to overuse. 