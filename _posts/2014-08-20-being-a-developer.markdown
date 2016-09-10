---
layout: post
title:  "Version control Development enviroments"
date:   2014-08-20 12:29:39 +0200
categories: development enviroment vcs
image: wood-nature-sun-forest.jpg
---


<h1>Version control &amp; Development enviroments</h1>

<h2 id="being-a-developer">Being a developer</h2>

<p><span class="intro">“Inhale… and exhale. Relax and keep working.”
Not really how it is to be a webdeveloper all the time. This post is about how to get more breathing room and make sure that your misstakes will not matter.</span></p>

<h2 id="the-first-step-to-give-yourself-breathing-room">The first step to give yourself breathing room</h2>

<p>Version control; relax and let yourself experiment with diffrent files by branching out to a separate branch.
Git checkout -b branchname</p>

<h2 id="expanding-on-vc">Expanding on VC</h2>

<h3 id="services-and-branches">Services and branches</h3>

<p>Have a service listen to your repo and set it up to listen for changes on  branches for changes and commits, and upon commits deploy to the server, being it production or live.</p>

<h3 id="tags">Tags</h3>

<p>A topic I’m not super enlightened in, are tags. Haven’t used tags in git at all. Wonder what it is meant to do.
Listened to a podcast while writing this actually (web ahead) and in the episode i listened to they mention it, didn’t stick in my head though.</p>

<p>Take a listen yourself: <a href="http://5by5.tv/webahead/79">WebAhead episode 79</a></p>

<h2 id="local-is-fast">Local is fast</h2>

<p>Everybody should have their own development/production enviroment. VM or server at haven’t figured out yet, but something along those lines would be optimal for a safe and relaxed enviroment.</p>

<h2 id="workflow-style-guide-driven-development">Workflow: Style guide driven development</h2>

<p>Also a diffrent topic I recently read an article about, was working on the front-end straight into and from styleguides. What I think this would mean in practice, would be that from a concept/mockup you extract elements and develop them separately and put them and present them in a standalone enviroment to be expanded and prototyped upon and with. The elements would then be refined in the markup of the styleguide and eventually updated and iterated upon.</p>

<h3 id="get-strapped">Get strapped!</h3>

<p>Why I want to embrace this topic and kind of way of doing things, is because I want sites and apps; projects(!), to be built using kind of a framework. Every websites stylesheet should more or less be a bootstrap kind of framework, where all you have to do is add the diffrent classes to get the kind of component/element and behavior that you want.</p>

<p>The article meant that the work flow would mean working on the backend of things could be built simultaneously.
However I think this approach would require a longer startup time to initiate.
The benefits however would be the prototyping experience with the elements, and the OOP style of things.</p>

<p><a href="http://webuild.envato.com/blog/styleguide-driven-development/">Article on styleguide driven development from the Envato blog</a></p>
