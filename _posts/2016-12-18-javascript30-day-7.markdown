---
layout: post
title:  "JS30 D7: Array Cardio pt. 2"
date:   2016-12-18 7:46:01 -0600
categories: javascript30 frontend
---

Today's [JS30](http://javascript30.com) lesson had me focusing on additional methods for Array, including .every(), .find(), .findIndex() and .some(). I remember when I started using Underscores, and then Lodash a couple of years back and how eye opening it was to have all of these awesome utilities available for managing this stuff. I eventually stuck Lodash in my toolbelt and didn't look back. Doing things like _.findIndex and _.difference just felt so elegant that I never stopped to dig into the underlying native methods that were being used. There's something nice about relying on a tried and true library to take a variable like browser support and drop its level of risk down a few points. I'm not saying that browser support is guaranteed when using lodash, but the gotcha I encountered when testing a project earlier this year, because of my use of String.prototype.includes() was somewhat of a rude awakening and the cause for a mild headache at the time. I didn't realize that IE did not support this method at all and obviously, stuff broke.

There wasn't much to piece together in a fancy codepen today, much like in [day 4](https://jon.bukiewi.cz/javascript30/frontend/2016/12/15/javascript30-day-4.html) but I'm going to earmark this concept of Array methods. My goal is to really feel like I've mastered the use case for [these tools](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array), along with a better idea of the current support of each, so I'll make note to put together some custom examples soon.

For now, it's Sunday, much of it was spent with family and finishing up some shopping, so further code dive will have to wait. Looking forward to tomorrow!