---
layout: post
title:  "Summary of NordicJS 2016 September"
date:   2016-09-08 22:29:39 +0200
categories: webapp event
---

# Summary of NordicJs ''16

## NordicJS - What is it?
TL;DR A 2 day JavaScript conference in Stockholm [@nordicJs](https://twitter.com/nordicjs).

[Youtube playlist of all the talks](https://www.youtube.com/playlist?list=PLGP3VO5jDf8wIGu0Q-huhv2Wfy2G5trbj)

This year the conference was held at Munchen bryggeriet in Stockholm, a big venue for holding conferences and bigger kinds of meets. Approximately 800 people came to se the talks that were held for two days.

The speakers talk about things from js framework performance to how to create art using math or how to program a rasberry-pi to send you photos of your cat from your home.
Most of the talks are generally brief demos of the application or topic with purpose of get you kickstarted or inspired to learn more on the topic.

Talks were generally 30 minutes, with the exception of a few "ligtning talks" wich were shorter, 5 minute talks from people/businesses attending the conference.

## My Take away
TL;DR Prototyping and MVPs are great!

__The first take__ away was that anything you can imagine is possible
to program with just Javascript (another question is wether or not it
is the most effective).

__The second__ is that it is really great doing TDD and
prototyping. I'd rather do prototyping over TDD since prototyping
tests even the ideas and interfaces, rather than just the code. But I
still have much faith in writing tests.

__The third one__ is something I took from the first talk, the talk
from [Jeremy Keith](https://twitter.com/adactio) talking about the
resilient web, progressive enhancements and most importantly the power
of the URL; being able to post an URL wherever on a post-it and
whomever goes to that URL can instantly install your service, right
then and there, from any device with just a browser. That message and
point talks about how powerfull of a media the web really is.

## The talks
**There were alot of great talks and I was totally exhausted and super filled with inspiration at the end of each of the days, so I will only tell of the talks I remember the most.**

### Jeremy Keith 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">3-steps process to build a better product by <a href="https://twitter.com/adactio">@adactio</a> <a href="https://twitter.com/nordicjs">@nordicjs</a> great presentation 😲🙉🖒 <a href="https://t.co/WHwH0Mo9CT">pic.twitter.com/WHwH0Mo9CT</a></p>&mdash; Tiago Lopes Ferreira (@ferreiratiago_) <a href="https://twitter.com/ferreiratiago_/status/773803391646568448">September 8, 2016</a></blockquote>
  <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

  His talk bout resilience. The first talk everyone was super pumped exited
  to be at #NordicJs, we were not yet annoyed by the pressing heat and
  low amount of oxygen, and this ,really original guy came up and
  talked us through some history how things came about, and how stable
  some things were, and how unstable some other things were.  Then he
  told us his methology and approach to things, and everyone was super
  inspired! [Blog about resiliance](https://adactio.com/journal/11130)
  
### Tomomi Imura
TL;DR Take photos of cats with Javascript

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">It was super nice to speak in front of awesome audiences at this amazing venue! 🐟 My slides are avail at: <a href="https://t.co/mDLRrKL6hF">https://t.co/mDLRrKL6hF</a> <a href="https://twitter.com/hashtag/NordicJS?src=hash">#NordicJS</a></p>&mdash; Tomomi ❤ Imura (@girlie_mac) <a href="https://twitter.com/girlie_mac/status/773848163765682177">September 8, 2016</a></blockquote>
 <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

 Her talk was "From Software to hardware", a talk and a case study how she with JS and a ras-pi take photos of her cat.
 
 She walked through how she setup and installed node on a ras-pi, then setup all the things in order to make the ras-pi work a camera, check for movement, take photo, scan said photo for cat faces with an algoritm, if there was a cat in the photo: send imageURL as a text to Tomomi.
 The project is live and she keeps getting loads of texts and enjoying it!
 
 
 
### Ashley Williams
TL;DR Separate the hard things from the easy things with modules.

[Ashleys slides: A-brief-history](http://ashleygwilliams.github.io/a-brief-history/)

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">zomg lol-ing so hard at these commit messages to my <a href="https://twitter.com/hashtag/nordicjs?src=hash">#nordicjs</a> talk. i do not remember these at all 😅😂 <a href="https://t.co/wrf11sMszh">pic.twitter.com/wrf11sMszh</a></p>&mdash; amster_dubs 🇳🇱 (@ag_dubs) <a href="https://twitter.com/ag_dubs/status/775001056816357377">September 11, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

I thought Ashleys talk was very philosophical, and she kept on asking philosophical  questions about 'why' and 'what is modularity?' and followed them up with quotes from philosofers.

Ashley showed[stats](http://ashleygwilliams.github.io/a-brief-history/#87)  started giving you performance issues when you had too many modules in your code. Fewer modules resulted in greater performance for your application.

In the talk there were some more stats on how NPM has grown and even more philosophical questions, but my main take was just what I said in the beginning, separate the hard parts form the easy ones in your code.

### Evan You
TL;DR Performance test-results depends on scenario-testing and circumstances

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Slides Afrom yesterday’s talk: <a href="https://t.co/4Nh8WOXEb2">https://t.co/4Nh8WOXEb2</a></p>&mdash; Evan You (@youyuxi) <a href="https://twitter.com/youyuxi/status/774163138052624384">September 9, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

Evan was the person I did the 2nd most research on (I watch alot of [#funfunfunction](https://www.youtube.com/channel/UCO1cgjhGzsSYb1rsB4bFe4Q)), I started doing a resume site with Vue for testing it out partly.

Evan talked about JS Framework performance, and taught us how diffrent architectures handle diffrent scenarios worse/better depending on some circumstances. The conclusion was that we should all take performance test-results with a grain of salt, and atleast run the scenarios we intend using diffrent tools for their intended purpose before we be the judge if it is correct or not.

Like some frameworks handle rendering small changes deep into the component-tree very well, while it might do inital render and full re-renders poorly. While other frameworks might be super fast at inital render and do full re-renders at blazing speeds.

He was the first one mentioning doing a protoype in order to actually test if the tools/framework was a viable option for the project you had in mind. Not relying too heavily on generic test-results.
 
### Vitaly Friedman
TL;DR Dirty dirty front-end tricks with css [calc()](https://developer.mozilla.org/en-US/docs/Web/CSS/calc) and cool email hacks with :checked that no project manager or sales person must be aware of.

Vitaly is editor-in-chief at [Smashing Magazine](http://smashingmagazine.com/), and he was the one starting the second day, he brought candy (I caught the first one he threw, epic catch!) and alot of energy and humor.

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Using a width value not to set the width but to trigger which of min-width and max-width will set the actual width. Mind. Blown. <a href="https://twitter.com/hashtag/nordicjs?src=hash">#nordicjs</a></p>&mdash; Anders Bornholm (@osirisguitar) <a href="https://twitter.com/osirisguitar/status/774162063757193216">September 9, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

He showed us really cool tricks for responsive font-sizeing and how to do interactive progressively enhanced emails, all with zero media-queries. The tricks were cool and inspiring and a bit horiffying with what you actually can do with email!

### David Björklund
TL;DR Do performance tests in TDD

<blockquote class="twitter-tweet" data-partner="tweetdeck"><p lang="en" dir="ltr">&quot;look at code to delete&quot; if you want to do some performance 🤘💣😈  <a href="https://twitter.com/david_bjorklund">@david_bjorklund</a> <a href="https://twitter.com/nordicjs">@nordicjs</a> <a href="https://t.co/8Hbba4xPxY">pic.twitter.com/8Hbba4xPxY</a></p>&mdash; Tiago Lopes Ferreira (@ferreiratiago_) <a href="https://twitter.com/ferreiratiago_/status/774196931262373889">September 9, 2016</a></blockquote>
<script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>


When working in some projects and doing some kinds of services, there may after a while in production/development come up issues on certain occassions, maybe even uncomfortable occassions.

Performance matters, and sometimes the cases in wich performance lags behind might not be all that appearant until you test for them. Also, doing performance tweaking is easier earlier in the process rather than refactoring an already matured codebase.


### Mattias Petter Johansson @mpjme

"If you know map, I will teach you monads"
<iframe width="560" height="315" src="https://www.youtube.com/embed/9QveBbn7t_c?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>
 
### Irina Shestak
TL;DW Visual patterns from mathematical rules

<iframe width="560" height="315" src="https://www.youtube.com/embed/VvON2C-Hfo8?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>

A week almost after the event, MPJME and Irina did a collab and together they made a Cellular Automata it is actually not that fun to code them, but the results are really nice too look at.


### Jem Young
TL;DW ESNext is easy to grasp, service-workers are aweseome!

<iframe width="560" height="315" src="https://www.youtube.com/embed/CRjGt0KfjzE?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>


## Outro
I had a great time at #nordicJS and if you want to read more what other had to say about the conference, I suggest to scan the hastag [#nordicJS](https://twitter.com/search?src=typd&q=%23nordicJs).

If you want to watch more of the talks they uploaded all the talks to youtube and saved them in an unordered [playlist here](https://www.youtube.com/playlist?list=PLGP3VO5jDf8wIGu0Q-huhv2Wfy2G5trbj).
