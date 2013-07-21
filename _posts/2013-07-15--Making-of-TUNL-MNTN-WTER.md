---
layout: post
title:  TUNL-MNTN-WTER&#58; a peek behind the scenes
author: sigveseb (& ...)
image: http://example.com/screenshot-of-the-demo.jpg
ingress: We released our second proper demo last week at Solskogen 2013. Here is what we learned.
---

# TUNL-MNTN-WTER: a peek behind the scenes

Ninjadev started dabbling in the demoscene last year when three of us visited our first demo party last summer.
For those not in the know, the demoscene is a computer art subculture where the main focus, apart from partying, is on creating demos - computer programs that generate audiovisual art in real time.
Solskogen 2012, the of the biggest demoparty in Norway, welcomed us with open arms, and we released a web demo called [HONEYCOMB](http://pouet.net/prod.php?which=59501).
This year twice as many of us went, intent on making a demo that was at least longer than last year's demo, which clocked in at about 1 minute and 30 seconds - about as much time as it takes to *insert silly yet ordinary thing which takes about 90 seconds*.

## Why begin now when you can begin later?

Time management is a fickle mistress, and although we knew [for the longest time](http://www.youtube.com/watch?v=a_XgQhMPeEQ#t=32) that we wanted to make a demo for Solskogen 2013, actually getting started is really hard.
As it turns out, people have lives, and finding time for demo making is not always the easiest task.
Work on TUNL-MNTN-WTER started a small week before Solskogen, with most of the work put during the first evening/night of the party.
Of course, doing to much demo coding at a party means missing out on a good deal of partying, so lesson learned.
Funnily, this is the exact same lesson that we learned at last year's Solskogen, but next year will be different!

## Choosing a language/framework

Our first demo was a JavaScript-powered web demo using WebGL with [THREE.js](http://threejs.org), and we wanted to do something different this time around.
We spent ages mucking about with different combinations of c, c++, opengl, lightweight framework x, heavyweight framework y, but eventually gave up.
A hard requirement for us is decent cross-platform compatibility, because we all develop in wildly different environments, ranging from Windows 8 through OS X Mavericks to Arch Linux, and most things inbetween.
Even getting simple C++/opengl snippets to run reliably on the different platforms was prohibitively hard (how do you guys do it, people who have managed it?!), so in the end, with the compo deadline looming nearer and nearer, we settled on making a JavaScript-powered web demo using WebGL with THREE.js.

## The music

The music was composed before a single line of code for the demo was written.
Because of this, the composers had an enormous amount of thematic control for the demo.
Inspired by Pat Metheny's "Last train home", the soundtrack for the demo was chugged out over the course of two days, in which the composers spent most of their time making appearances at Martini parties.

## Some facts about the train, with cool graphs

Seeing as none of us are graphic artists or even know how to work our way around a 3D modelling program, we were kind of limited in terms of train design.
We quickly resorted to purchasing a train model [online](link-to-the-train-model).

## Shaders: turns out that they rock and are cool

### The ascii shader

anecdote about honeycomb's crazy hack trick

## Hard-coding everything vs making a tool

quote: the }]}])}]}]]}]};-line from honeycomb

## Next year: more awesomeness!
