---
layout: page
title: Personal Work
permalink: /personal/
---

## Visual Effects

## Tools & Automation

### Unreal Effect Viewer

The previewing capabilities of Niagara are limited, especially when working with gameplay VFX that needs to be evaluated in an in-game context. 

To simplify iterating on gameplay VFX, I built a previewing tool that lets the artist control the playback in a controlled manner. And since the tool is operated using Play In Editor, you know that the effect is being rendered correctly. 
 
### NodeFX 

As a proof of concept, I came up with a way to let artists create Particle Systems in Unity through the use of VOP networks in Houdini. This let the artist set up sophisticated relationships and behaviors not otherwise possible in Shuriken

For this workflow, I used Houdini's Python implementation to evaluate the VOP network and bake it down to a JSON file, which was interpreted in Unity using C# to generate the particle system.

<iframe src="https://player.vimeo.com/video/259976226?h=97f7c90ca9" width="640" height="564" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>

### This Website

I am by no means a web developer, but I felt clever setting up this website. It is statically generated from Markdown using Jekyll. The site is hosted on GitHub, and has a worker that is triggered with each commit to regenerate the static pages. I can even update this website using git on my iPad!

A breakdown of the workflow can be found here: [Creating a digital CV in Markdown using GitHub Pages by Carolyn Stransky](https://workwithcarolyn.com/blog/digital-cv-guide)

## Art

### Digital

### Traditional