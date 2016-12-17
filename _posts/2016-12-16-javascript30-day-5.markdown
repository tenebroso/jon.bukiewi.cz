---
layout: post
title:  "JS30 D5: Fun with Flexbox"
date:   2016-12-15 8:47:01 -0600
categories: javascript30 frontend
---

<p data-height="665" data-theme-id="0" data-slug-hash="woRpdb" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 5 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/woRpdb/">JavaScript 30: Day 5 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I've dabbled in flexbox and feel like I am comfortable enough with it to just be behind on the curve on knowing anything about [CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/). Alas, the web never stops evolving and feeling slightly behind has to come with the territory for most developers. At least it does for me! However, it's tutorials like today that keep me hopeful because they remind me of how *fun* web development can be. Clicking on any of the above panels expands that panel to 5x its default width. Once the size has been increased, the additional text slides in from the top and bottom.

If I had been tasked with re-creating this from scratch myself, the first deviation I would have made is to rely on some sort of CSS animation delay in order to slide the words in after the panel had finished expanding. Once again I'm amazed by the use of setting an eventListener on the transition property of a CSS animation, then further dialing into it by targeting the property itself within the ensuing function. I've always pigeon-holed eventListeners into being associated with "click" and little else. It's freeing and exciting to know how much more that can be done!

I also hadn't really explored flexbox nesting, or vertically aligning elements. My experience has mostly been with l-to-r alignment of elements such as in layouts like the [share cards](http://www.westernusa.salvationarmy.org/usw_thq/style_guide#shareCards) or [stripe callouts](http://www.westernusa.salvationarmy.org/usw_thq/style_guide#stripesStoryCalloutWithPhoto) of a recently finished project.

Also, I had a small freelance tweak on an old client site tonight and opted to use vanilla JS instead of jQuery (which was already loaded) as an exercise in putting more of this stuff into practice. It went really well. I think the overall approach was slightly more verbose than using jQuery would have been, but it's worth it. It feels good to be breaking out of old habits and I'm excited for tomorrow!

As a side note, I went ahead and picked up Wes's courses on [ES6](https://es6.io) as well as [React for Beginners](https://reactforbeginners.com/) a couple of days ago. I can't deny the fact that JS development is going to continue to be apart of my career path (hopefully!) and future interests for a long time to come, so I want to keep motivated to learn all that I can. Wes has a great teaching style that is down to earth and understandable, so I'm happy to stick with him as my go-to instructor!