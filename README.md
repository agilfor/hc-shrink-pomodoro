# Tiny Pomodoro

A tiny interpretation of a pomodoro timer to help you focus on your work and keep track of how long you've been grinding. The timer can be set to any time you want, and you can add up to 5 tasks to help you remember what you're meant to be doing.

This project is part of the Hack Club [Shrink program](https://shrink.hackclub.com/), for which the goal is to design a website under 3KB that can be converted to a data URI. The URI can be found in [uri.txt](./dist/uri.txt). The total size of the URI is 3071/3072 bytes.

## Process

This project was designed in increments. I started with the timer and trying to figure out colors. Then I also added tasks and finally a help tab. At the end of this I was at roughly 5KB, so I spent a good while trying to figure out how to shrink the size of the URI. I did this through removing every unnecessary bit of text I could find (unneeded quotations, tags, shorter variable names, etc.), and by optimizing the JS and CSS logic as much as possible. I wrote all of this myself, with some help from the docs and the occasional AI query to avoid reading massive pages of docs or to find more efficient ways to do things.
