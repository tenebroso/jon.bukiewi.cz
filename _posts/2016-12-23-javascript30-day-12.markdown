---
layout: post
title:  "JS30 D12: Key Sequence Detection"
date:   2016-12-23 11:59:01 -0600
categories: javascript30 frontend
---

Today's lesson was a pretty straightforward example of listening for keyup events in order to reproduce some of the KONAMI easter eggs that exist on some of the sites out there. We utilized pushing keystrokes to an array, joining them into a string and then checking on whether or not they match the provided code. To test it out, every time you type "jon" in on this page, you'll get a surprise!

<script type="text/javascript" src="//www.cornify.com/js/cornify.js"></script>
<script>
function load(){
	const pressed = [];
	const secretCode = 'jon';

	window.addEventListener('keyup', (e) => {
		pressed.push(e.key);
		pressed.splice(-secretCode.length - 1, pressed.length - secretCode.length);

		if(pressed.join('').includes(secretCode)){
			cornify_add();
		}
	})
}
window.onload = load;

</script>