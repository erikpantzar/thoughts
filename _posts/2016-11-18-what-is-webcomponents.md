---
layout: post
title:  "What is web components? 2/3"
date:   2016-11-18 01:02:39 +0100
categories: semantics, html
---

This is part of a three part series:

1. [What is semantic HTML?](/thoughts/2016/11/what-is-semantic-html)
2. What is Web components?
3. [Are custom-elements semantic HTML?](/thoughts/2016/11/are-custom-elements-semantic)


# What is WebComponents?
I found out that W3C has divided it into [three parts](https://www.w3.org/wiki/WebComponents/) (shadow DOM, Custom Elements & HTML Imports)


### Shadow DOM
The W3C [Shadow DOM spec](http://w3c.github.io/webcomponents/spec/shadow/)

My understanding of Shadow DOM is that with Shadow DOM you can contain and scope HTML, CSS & Javascript without the need for any special tooling etc, just plainly scope it to its own little thing.

### Custom Elements
The W3C [Custom Elements spec](http://w3c.github.io/webcomponents/spec/custom/)

My understanding of CustomElements is that they are meant to define themselfs for the parser (browsers) and thereby be accepted as and rendered as regular HTML elements.
The Custom Element in turn can have other elements inside of itself and functionality and trigger and listen to custom events and change its own scope.

I just saw a [video with a talk about webComponents](https://youtu.be/XYlgxre_AF4) in wich they inspect the ```<video>``` element's shadow DOM and finding divs and inputs and buttons that in turn make the ```<video>``` element with its nested element, styles and functionality. The video mentions that the features most of us use and develop features in will soon be native web features, thereby ending the need of certain Javascript-frameworks.

### HTML Imports
The W3C [HTML Imports spec](http://w3c.github.io/webcomponents/spec/imports/)

My understanding is that this part is meant for managing and getting WebComponents into your application/feature. The pattern used is similar to how we today import stylesheets: ```<link rel="import" href="/imports/heart.html">``` and tada, you have access to your webcomponent just like that!


## How to build a WebComponent
I will not go through that in this text, but if you want to know more, I would checkout:
- [Polymer.js](https://www.polymer-project.org/1.0/start/)
- [Guide to WebComponent 2013](https://css-tricks.com/modular-future-web-components/)
- [Web Components and Aria](https://www.paciellogroup.com/blog/2012/07/notes-on-web-components-aria/)

How to build a WebComponent and use it today, that is entirely up to who you want to be able to access it. There are Polymer.js and I bet even more libraries that help you with this. Also there are polyfills for many of the features to ensure it works.

### Browser support
Found this hopeful article reading up on how to build components for the current section:
 [**Browser Support** _from developers.google.com_](https://developers.google.com/web/fundamentals/getting-started/primers/customelements?hl=en#browser_support)
