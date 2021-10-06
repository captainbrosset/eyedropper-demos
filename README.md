# EyeDropper API demos

This repository contains a series of simple demo pages made to showcase the new JavaScript [EyeDropper API](https://wicg.github.io/eyedropper-api/).

## Why this API?

Sampling colors from your screen is a very useful feature in creative applications. PowerPoint lets you change things like the color of a shape by sampling from other shapes. Photoshop also allows you to sample the color of any pixel in the screen to reuse for your drawings. Finally browser DevTools also allow you to grab the color of elements in the web page when editing color properties in the Styles panel.

It is, unfortunately, not possible for web applications to do this today. Some browsers do support it if you use an `<input type=color>` element, but that means you're forced to use the input element for something you might want to do in JS only and customize to your needs.

The EyeDropper API aims to fill that gap.
