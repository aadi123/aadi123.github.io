+++
title = 'The Importance of PPI'
date = 2023-12-09T21:31:44-06:00
description = 'My first blog post'
+++
This is my first blog post!! I will attempt to introduce myself and
my motivations for starting a blog, and also attempt to convince you
why PPI should be a big factor when evaluating the quality of a display.

## Introduction
Hello dear readers, and welcome to my blog! If you've managed to make it this far,
Congratulations! The state of the blog and is still in-progress and will evolve over time, and I appreciate
you taking the time to read it in spite of its limitations.

### About Me
Hi! I'm Aaditya Murthy. Currently, I am working on the Video Ingestion team at Toyota Connected as a Software Engineer. Previoiusly I worked at Amazon as a Software Development Engineer for the past two years. I completed my Bachelor's in Computer Science from UT Austin in 2020.
I like to sing, play chess, and run for fun, and I dabble in some other things as well (Music Production, video-games, game-streaming, and much more).
Anyways, I wanted to start a blog mostly to blog about interesting topics within Computer Science and Mathematics,
but I hope to also blog about other things (life, music, etc.) as well! Let's see where this goes, and I sincerely hope that you as the reader will find some value in it!

## What is PPI?
With that out of the way, I'd like to introduce the topic I have chosen for this post, PPI. **PPI** or *pixels per inch* refers to the number of pixels in an inch on the display. The two factors that influence PPI are screen size and resolution. The larger the screen size for the same resolution, the lower the PPI. The higher the resolution for the same screen size, the higher the PPI.

## Why is it Important
PPI is important because it represents how big/small the fonts/GUI/Applications look on your screen, and how much usable screen real estate you have on your display.
Having too low a PPI means not having enough screen real estate, and having too high a PPI means your apps and fonts will look tiny.

I would like to also introduce this post for further reading on the topic [What is HiDPI](https://cassidyjames.com/blog/what-is-hidpi/). This post
does a great job of explaining why PPI is important. But the TLDR is:

- HiDPI ideally means pixel-doubling (twice as many in each direction so 4x the number of square pixels)
- Half pixels are a lie
- 4K does not mean HiDPI, and might not always be the best resolution
- Some manufacturers make poor decisions

> For example, on a 15” display, 1080p (1920×1080) at 1× scaling produces a great usable amount of real estate without the fonts and icons being too small. 1080p pixel doubled is 4K (3840×2160), so that makes sense on that physical size; everything will be the same size, but twice as crisp. However, on a smaller display like 12 or 13”, 1080p at 1× is far too dense (meaning the UI is far too small) for most users. So 4K on this physical size is actually worse than something like 3200×1800 (equivalent to 1600×900 pixel doubled).

The reality of the fact is, most manufacturers these days slap some sort of hi-res display on every device in order for it to sell well. However, what should matter more is the actual PPI of the display, or how much screen resolution you're getting at a specific screen size. A good rule of thumb to follow is to hit around 120 PPI for desktop monitors and 140 PPI for laptop screens (add a range of about 16 PPI above and below the target as wiggle room). This makes 1080p/4K a perfect resolution for 14"-17" laptop displays. Many laptops I've seen are now coming with Quad-HD displays (2560x1440) which actually run into the big problem of software-based fractional scaling, as described in the above article, leading to fuzziness, bluriness, and generally reduced clarity of text and apps.

I hope to blog more on varied topics in the future, let's see where this goes :).