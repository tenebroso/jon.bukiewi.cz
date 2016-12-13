---
layout: post
title:  "JavaScript 30: Day 1"
date:   2016-12-12 10:27:49 -0600
categories: javascript30 frontend
---
Today I began Day 1 of Wes Bos' [JavaScript 30](https://javascript30.com/) course and I think this is going to be pretty awesome. We made a drum keyboard (mine: http://codepen.io/tenebroso/pen/YpOMLK?editors=0100) and I was able to dabble in ES6 for what has honestly been the first time. I ended up in a bit of a rabbit hole through exploring the differences between const, let and even var. 

I came up with this:

{% highlight js %}const
// Its value cannot be changed or redeclared.
// Cannot be overridden by var or let.
// However, within the scope of a block it can be redeclared. 
// Cannot override its objects or arrays as a whole, but values can be edited individually.
{% endhighlight %}

{% highlight js %}let
// Is only relevant in its current block scope
// Will never create a property on the global window object
// Cannot be redeclared within the same block/function
// Cannot be referenced before it is defined
{% endhighlight %}

I also had no idea that adding any kind of event listener having to do with CSS was even possible. I have a lot to learn. Can't wait for tomorrow!
