---
layout: post
title:  "JavaScript 30: Day 2"
date:   2016-12-13 6:55:49 -0600
categories: javascript30 frontend
---
Day 2 is in the books! Today with the help of Wes' great tutorial, I built a CSS/JS-based [clock](http://codepen.io/tenebroso/pen/PbyOVg?editors=0010). I found an SVG clock face and went ahead and dropped it in for additional affect.

Things I learned:

- transform-origin is a pretty great way to adjust the point at which a rotation occurs on an element. I'm not sure why I haven't encountered this before, but it's been off my radar until now. It was the only way to get the hands of the clock to spin from the center of the clock, rather than spinning on their own center axis. This was achieved by setting transform-origin to 100%;

- That the Date() object is more powerful than I realized. I've been opting to use MomentJS on most projects as the default, much like jQuery. It was interesting to explore what capabilities are built in besides just getting the current date, such as getSeconds, getMinutes &amp; getHours. Seems so obvious now, but I've just never had a case (that I knew of) to rely on these. 

I'm really excited moving forward to see how far I can get without jQuery and now without MomentJS. These are both awesome tools, but I will be the first to admit that I've overused them!