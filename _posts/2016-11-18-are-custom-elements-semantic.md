---
layout: post
title:  "Are custom elements semantic HTML? 3/3"
date:   2016-11-18 01:03:39 +0100
categories: semantics, html
---

This is part of a three part series:

1. [What is semantic HTML?](/thoughts/2016/11/what-is-semantic-html)
2. [What is Web components?](/thoughts/2016/11/what-is-webcomponents)
3. Are custom-elements semantic HTML?

# Are custom-elements semantic HTML?

TL;DR Yepp..

When you are certain of a thing, you don’t have doubt and you can act faster. Building web apps while also being concerned with semantics and approaching it from a native HTML-element view, doing custom element/component architecture give you doubts and slows you down. With this article I plan on finding out and get my own idea on how to approach this.

Working with people with strong opinions on native-HTML and semantics and mixing that up with Javascript-frameworks that embrace custom-elements, I feel that my current knowledge of what semantic markup is, only reach as far as what HTML5 element suit where, and when building custom-elements I’m not sure how to motivate it semantically technically and in comparison with using a heading for a heading etc.

## Two kinds of semantics

I wrote shortly about semantics and looked up definitions of semantic HTML that make sense, but I would also like to talk about semantics with the concern of screen-readers and to build accessible project for people with different disabilities, the other kind is semantics with just the concern of what the element does and what it should consist of with the idea of maintainability and development.

## Screen-readers and browsers

Aria roles and Tab index are two tools that help screen-readers and people that navigate with tools other than for example the mouse. These two should be used both for ordinary HTML-elements as well as with custom-elements.

## Humans

For fellow developers (also future-self fit in this category) semantics is important to build with semantics in mind due to elements that do and are what they are called are easier to grasp and find its source in order to further develop and maintain them.


## Examples of semantic Custom Elements

I feel that this is not final, what I’ve concluded from my research working and writing this article.

This would be my ordinary HTML markup and structure (imagine that without declarative classes, then it could have been just a blogpost or w/e):

```
    <article class=product>
        <header>
            <figure class=product-images><img /></figure>
            <figcaption />
        </header>
        <div class=product-content></div>
        <aside class=product-sidebar>
            <a class=store-locator-toggler></a>
            <div class=store-locator-container></div>

            <div class=product-review-container>
                <h2/>
                <ul class=product-review-list>
                    <li class=product-review-item />
                    <li class=product-review-item />
                </ul>
            </div>
        </aside>
    </article>
```


The following would be my custom element markup:

```
<product>
    <product-content />
    <aside class=product-sidebar>
        <store-locator/>
        <product-reviews/>
    </aside>
</product>
```


I feel that it is more declarative and semantic to be using custom elements over HTML5!


What I wanted to and have explored in this article, was how and if Web components were accepted as a semantic part of the web. And with it soon being a part of the web standards we surely can say that it is soon not just a nice feature of our beloved Javascript frameworks but web standard!

## Re-usability

Custom-elements are intended to be portable and reusable in entirely different projects, but for the most part when I come across them is as reusable components inside the architecture of a Javascript framework though.

```
    // Category page
    <product-item/>

    // Search listing
    <product-item/>
```


## Semantica11y

Besides the idea of reusability, they are semantic to the degree of how you name them, a will and probably is project specific in the case i can refer to, but you can immediately tell what the tag will present you with as a human & developer.


## Outro / Conclusion

So get out there, learn how to write custom elements today already, or just keep an eye out for when they become web standards!

Until then let’s just build things for all the peoples! =)
