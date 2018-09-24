---
layout: post
title: "Understanding colourblindness"
description: "What is colour blindness, and how can we design with it in mind?"
author: matthew_higgins
published: true
categories:
  - Background
---

Colourblindness is a common genetic condition in which some peoples' eyes can't tell the difference between certain colours. That's not to say they see everything in greyscale-- just that many colors seem identical to one another. Total colour blindness is very rare in humans.

Colour vision deficiencies (typically grouped together as "colour blindness") are not rare. Some form of colour blindness affects at least one in twenty people. [Wikipedia has a helpful table](https://en.wikipedia.org/wiki/Color_blindness#Epidemiology), based on [a journal article](https://apfmj.biomedcentral.com/articles/10.1186/s12930-014-0010-3). There are [several different forms](http://www.colourblindawareness.org/colour-blindness/types-of-colour-blindness/). The most common, red-green colour blindness, affects around one in twelve men.

Colour blindness is less profound than many impairments, but people with colour vision problems often face restrictions on certain activities. This varies around the world. For example, Romania prohibits residents who are colour blind from driving. The USA doesn't consider colour blindness a disability because of workplace discrimination purposes.

Though there are multiple types of colourblindness, they are the same in principle. For more information, check out [Wikipedia's article on colour blindness](https://en.wikipedia.org/wiki/Color_blindness), which has some excellent descriptions.

## What does this mean for accessibility on the web?

To make sure your site is readable for individuals with colourblindness, avoid relying on colour alone to communicate.

These guidelines are compliant with the WCAG; guideline [1.4.1 covers making content distinguishable using colour](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-without-color.html).

In practice, you can achieve this by choosing colors that are easily distinguished from one another, and by adding secondary visualizations for icons and tasks. For example, you're using red and green buttons to represent tasks a user has outstanding. It might seem logical to show items that need attention in red, and those that are good in green. One small change, such as overlaying a check mark icon over the "good" or "completed" items, will help determine which items are approved and which need attention.

There are cases where this isn't possible. The periodic table, for example, often colour-codes the chemical symbols of the elements. When working with tables or other standardised layouts, adding more text or symbols might not be practical. 

## Available Tools

There are a number of online tools to help those without colourblindness visualize how accessible their designs are:

- [Colorblind Color + Contrast Picker] (http://colorsafe.co)
- [Colorblind web page filter by Toptal](https://www.toptal.com/designers/colorfilter)
- [I want to see like the colour blind Chrome extension](https://chrome.google.com/webstore/detail/i-want-to-see-like-the-co/jebeedfnielkcjlcokhiobodkjjpbjia)

These tools are free, simple to use, and can quickly help designers and developers make colour-accessible choices. 
