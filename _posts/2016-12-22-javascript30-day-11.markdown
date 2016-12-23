---
layout: post
title:  "JS30 D11: Custom Video Controls"
date:   2016-12-22 11:59:01 -0600
categories: javascript30 frontend
---

<p data-height="565" data-theme-id="0" data-slug-hash="aBrbWa" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 11 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/aBrbWa/">JavaScript 30: Day 11 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I have gotten by pretty well in using native YouTube APIs or Vimeo embeds along with tools like [FitVids](http://fitvidsjs.com/) for handing responsivenss, but that's mainly been because there has not been a strong need for custom styled video controls in my past projects. Today's [lesson](https://javascript30.com/) equipped us with some tools that can be used to build our own video player with customized controls. I think this was another powerful example of really exposing the native methods and properties can be found by default. I used to think of elements on a page as being totally without meaning on their own, without the inclusion of some library to expose state, properties or create methods. Who knew that the video element set its own updatetime property and that it could be used as an eventListener in order to update a progress bar? These have generally been abstracted away in my own head, rather than something that I could target natively. Again, I am really grateful for console.dir(el) as we continue this course!

I took Wes' challenge to implement a full screen button on my own and ended up down a bit of a rabbit hole in reading about browser support. From what I could find, there are multiple vendor prefixes required for something like this to be used natively, so in the above example rather than including all of them I went ahead and just set this up to work in Chrome, as proof of concept. 