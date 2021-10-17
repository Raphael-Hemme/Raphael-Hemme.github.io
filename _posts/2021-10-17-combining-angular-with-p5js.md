---
title: "Combining Anguar and p5.js"
categories:
  - Blog
  - coding practice
tags:
  - resources

---

## The Problem

When trying to use p5.js inside an Angular app a week or so ago, I struggled to find instructions or tutorials on the matter that were working and up-to-date. One of the tutorials was a bit outdated but still very helpful once I figured out how to get rid of the error messages that immediately poped up when trying to set it up with a more recent Angular version (12.2).

But first let's get two questions out of the way: 
- 1. What is p5.js and 
- 2. Why even bother using it inside an Angular app?

### What is P5.js
p5.js is a library for creative coding. It provides functions or tools that make it easy to generate or manipulate images, video and sound. That makes it -among other things - particularly useful for creating generative art.

### Why use p5.js in a framework like Angular 
While p5.js gives us quite a few options to interactively react to user input like keypresses or mouse movement, at this point, I think it is much more convenient to use a web-framework like Angular (or React, Vue, Svelte ...) to build a site around the sketch and handle data-flow and rendering in a reactive manner while allowing p5 to shine on the canvas.

## Base Setup

### Create a fresh app with the CLI

### Install p5.js into the app

### Change strict-mode to false

