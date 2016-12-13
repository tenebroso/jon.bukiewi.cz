---
layout: post
title:  "JavaScript 30: Day 1"
date:   2016-12-12 10:27:49 -0600
categories: javascript30 frontend
---
Today I began Day 1 of Wes Bos' [JavaScript 30](https://javascript30.com/) course as a way to level up my JS skills and, well, because I'm a sucker for "30 day" challenges. This course in particular is intriguing because of the way in which the primary focus is vanilla JavaScript, rather than any frameworks or libraries. I've often defaulted to relying on lodash, jQuery, Angular, etc as a starting point without really feeling like I have a firm grasp on the underlying foundation. Compared to a library or a framework, vanilla JS isn't sexy to me, but it doesn't mean I should neglect it. I want to know the capabilities of what can be done strictly in the browser so I can better understand what a framework would actually be doing in my projects. 

My goal is to write out a few thoughts for each of the 30 days - even if they are scattered notes. I learn better by re-iterating what it is I've seen and then done myself, so this will be an experiment in really having this material stick.

In day 1, Wes walked us through building a [keyboard-based drum kit](http://codepen.io/tenebroso/pen/YpOMLK?editors=0010). Mine is slightly altered aesthetically from the default, but I had to hack around a bit to really feel like I picked up everything that was shared - CSS included. I was able to dabble in ES6 for what has honestly been the first time. It's almost 2017, should I delete that sentence? No, it has to stay, I have to start somewhere. 

Anyway, with the ES6 stuff in there, Wes included the const statement which I have seen before but never really understood. On top of the awesome [keycode.info](http://keycode.info) resource for mapping keystrokes and the inclusion of a great walkthrough on using a transitionend eventListener to have JS watch for CSS animations, I ended up in a bit of a rabbit hole in exploring const and let. If I'm going to encounter these, I want to understand them fully.

I came up with the following thanks to [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const):

{% highlight js %}const
// Value cannot be changed or redeclared.
// Not overridden by var or let.
// Within the scope of a block, can be redeclared. 
// Cannot override its objects or arrays as a whole, but values can be edited individually.
{% endhighlight %}

{% highlight js %}let
// Only relevant in its current block scope
// Will never create a property on the global window object
// Cannot be redeclared within the same block/function
// Cannot be referenced before it is defined
{% endhighlight %}

I have a lot to learn and I am loving the process. 

Can't wait for tomorrow! Many thanks to [Wes](http://wesbos.com/) for putting this course together.