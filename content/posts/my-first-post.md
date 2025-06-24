+++
date = '2025-06-24T10:09:29-07:00'
draft = false
title = 'Game Dev with Amazon Q'
+++

Amazon is running a [jam](https://community.aws/content/2y6egGcPAGQs8EwtQUM9KAONojz/build-games-challenge-build-classics-with-amazon-q-developer-cli?trk=17fa81c7-a490-4008-bbc9-99ea0abacedf) to encourage use of Amazon Q. Why not give it a whirl? They suggest vibing a retro game using PyGame. I've written a lot of Python code over the years, and quite a few games, but never PyGame. I also haven't tried Q in a long time, when it was the _Code Whisperer_... time to see if it's improved.

## Getting started

I decided to create a Space Invaders clone. I started by writing a README.md with a fairly detailed description of the game, and the development environment.

{{< figure src="/images/shot3.png" alt="screencap of README" width="200">}}

Rather than use my own Python project template, I thought I'd let Q start from scratch to see how it does. I created another file to contain prompts to feed Q - I always try to document my prompts for continual evolution of my personal prompt library.

{{< figure src="/images/shot4.png" alt="screencap of prompt" width="200">}}

## Success on the first try!

The prompt was fired off, and a _lot_ of code was generated. Despite it's stated intention to write clean, well-structured, maintainable code... it still looks like internware to me. On the upside, it mostly worked on the first try!

{{< figure src="/images/shot5.png" alt="screencap of some generated code" width="200">}}

{{< figure src="/images/shot2.png" alt="screencap of game" width="200">}}

## Conclusion

Installing Amazon Q is pretty straightforward, but it insists on taking over your shell rc files - and that broke some of my important customizations.

It's ability to set up a running environment, creating functioning code, and create tests has improved a lot since the last time I tried it. It's probably not ready to be my daily driver yet but I'll keep an eye on it.
