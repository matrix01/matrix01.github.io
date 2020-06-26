---
title:  How to create custom template for Xcode
tags:
  - Template
  - Xcode
  - Swift
  - Viper
  - Architecture
---

For my last two project I had the opportunity to setup the base architecture for iOS project. Since most of my projects were in MVC until now it was hard to choose a Base Architecture. I learned two most popular architecture, MVVM with clean architecture and Viper. I will discuss more about choosing a architecture on later posts. While implemeting source code for projects I faced difficulty of creating many files that needs to be created at same format with some specific files. It was frustrating. So I started to look for a solution and the solution was right in front of me and it was creating module with those specific files. Vola!!! Problem solved.


### Where to start?


<!--more-->

The card allows a caption to be aligned with the photo, and the card classes contain a `card-img-top` that ensures the image is responsive within the grid.

<div class="card mb-3">
    <img class="card-img-top" src="https://drscdn.500px.org/photo/127767019/q%3D80_m%3D1500/v2?webp=true&sig=dd1fa4580c459472969cd4992068922f311f12cf263cf08b39615cfc1812286b"/>
    <div class="card-body bg-light">
        <div class="card-text">
            The Peak District on a mosty morning.
        </div>
    </div>
</div>

The HTML source for this card is below, or of course you could look at the raw source for this file in the GitHub repo or on your disk after you have downloaded the repo. WHen looking at the source, you can see the Markdown mingled with the HTML.

{% highlight html %}

<div class="card mb-3">
    <img class="card-img-top" src="https://drscdn.500px.org/photo/127767019/q%3D80_m%3D1500/v2?webp=true&sig=dd1fa4580c459472969cd4992068922f311f12cf263cf08b39615cfc1812286b"/>
    <div class="card-body bg-light">
        <div class="card-text">
            The Peak District on a mosty morning.
        </div>
    </div>
</div>

{% endhighlight %}