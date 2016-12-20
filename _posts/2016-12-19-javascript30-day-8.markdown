---
layout: post
title:  "JS30 D8: HTML5 Canvas"
date:   2016-12-19 9:03:01 -0600
categories: javascript30 frontend
---

Woww, ok - so [today's lesson](https://javascript30.com/) was especially mind blowing. Check out the codepen below, which allows you to click and drag in order to create a line which changes in hue and width as you move. 

<p data-height="565" data-theme-id="0" data-slug-hash="xRMNYJ" data-default-tab="result" data-user="tenebroso" data-embed-version="2" data-pen-title="JavaScript 30: Day 8 - Wes Bos" class="codepen">See the Pen <a href="http://codepen.io/tenebroso/pen/xRMNYJ/">JavaScript 30: Day 8 - Wes Bos</a> by Jon Bukiewicz (<a href="http://codepen.io/tenebroso">@tenebroso</a>) on <a href="http://codepen.io">CodePen</a>.</p>
<script async src="https://production-assets.codepen.io/assets/embed/ei.js"></script>

I'll admit, today was packed, so while I watched the walkthrough, I did not re-create this from scratch as I did the others. It's just how it will have to be today. I'm grateful for the introduction, but I don't see myself being able to create something like this without a pretty solid reference to multiple [MDN](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation) [tabs](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/getImageData), so when I do, I'll try to change it up a bit and make it my own. I'll add it to the list of takeaways, which seems to be growing.

That said, it was really the problem solving that I liked most about today's video. Wes was able to break down each feature into really logical steps and it resulted in a really elegant approach. How do you track the mouse cursor in order to start the line when it is clicked? How best do you handle colorizing the line? How can you add to and then subtract from the line width, reliably? Everything really "clicked" as he went through the process and it was great today to be able to see that type of clear approach to a visually complex project.