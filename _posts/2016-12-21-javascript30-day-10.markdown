---
layout: post
title:  "JS30 D10: Shiftin' on Checkboxes"
date:   2016-12-21 11:59:01 -0600
categories: javascript30 frontend
---

<p data-height="565" data-theme-id="0" data-slug-hash="zoXagR" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 10 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/zoXagR/">JavaScript 30: Day 10 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I really, really liked today's exercise of [JavaScript 30](https://javascript30.com/). The goal was to take the existing list of checkboxes and enable the user to check any of them, then hold shift and check another in order to select any other inputs between the two. Wes started out by explaining the problem at hand and then challenged us first to try it out on our own. I thought this was a great idea, especially since I've been itching to put some of the previous day's lessons into practice.

I made use of the ES6 arrow function and console.dir() came in really handy to see the properties of a given element. I left my original code as-is even though Wes's solution was ultimately a bit simpler. I didn't realize that an input element could pick up on the fact that shift was being held down, so I originally started out creating a separate check for that.

I admit that I did get stuck at one point, primarily when it came to the point of utilizing "this" when looping over the checkboxes. I struggle with "this" more often than I'd like and should probably just plan to console.log it more often in order to keep up with what it's referring to throughout the process. Wes had a solution of setting a flag for if the checkbox was either "this" (the one being checked) or the "lastChecked" (the previously checked input) and then assigning any inputs in the array to be checked if that flag was true. I think this solution turned out pretty elegant and brilliant and I'm happy with how things are coming along in my own learning. This was not something I could have tackled without some stress and jQuery just a little while ago.

I am purposefully leaving my original state intact, with the addition of Wes' final pointers which pushed me over the finish line. I know I had things set in concept, but the very last array loop and setting the flag tripped me up.

Also, I'm a little late on this blog post but who isn't in holiday mode at the moment? I'm ok with it.